pipeline {
	agent any
		stages {
			stage ("one") {
				steps {
					echo "This is branch 21q1"
				}
			}
		}
}
