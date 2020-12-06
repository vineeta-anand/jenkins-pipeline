pipeline{
    agent{
            label 's1'
	        }
		    stages{
		            stage('checkout'){
			                steps{
					                sh 'rm -rf pipeline1'
							                git changelog: false, poll: false, url: 'https://github.com/vineeta-anand/jenkins-pipeline.git'
									                sh """
											                sh example.sh
													                """
															                echo "checkout"
																	            }
																		            }
																			            stage('build'){
																				                steps{
																						                echo "build"
																								            }
																									            }
																										        }
																											}
