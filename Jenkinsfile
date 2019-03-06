node {
	stage("Build") {
		def mavenImage = docker.image("maven:3.6-jdk-8")
		mavenImage.pull()
		mavenImage.inside("-e someEnv=dev"){
			sh 'echo $someEnv'
		}
	}
}
