pipeline {
agent any
stages {
	stage("Checkout") {
		steps {
			git url: "https://github.com/fadouakhadir/calculator.git", branch:"main"
		}
	}
	stage("Compilation") {
		steps {
			sh "./gradlew compileJava"
		}
	}
}
}
