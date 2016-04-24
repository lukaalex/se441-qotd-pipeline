stage "SETUP"

node {
	git 'https://github.com/lukaalex/se441-qotd.git'

	def gradleHome = tool 'Gradle 2.11'
	sh "${gradleHome} assemble uploadArchives"
	
}