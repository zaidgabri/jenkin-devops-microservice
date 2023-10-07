//SCRIPTED  it comes with stages but also stages are not obligatoire to write so it optional also it comes with  the name  of oh the node 
//decalartive Pipleline we do not need a node Just the name pipeline 
// agent where the build going to run it same like node but it gives u more flexibilte enevn the docker images going to be a agent stages 
// stages are obligatoire to add , POST for adding conditions to the stages and checking about the status 

pipeline  {
		agent  any 
		stages{
			stage('Build'){
				steps{
					echo "Build"
				}
			}
			stage('Test'){
				steps{
					echo "Test"
				}
			}
			stage('Integration Test'){
				steps{
		
					echo "Integration Test"
				}
			}
		}
		
	 post{
			always {
				echo "I'm awesome. I run always "
			}
			success {
				echo "I run when u are successful"
			}
			failure {
				echo "I run when u fail "
			}
	
	}
}
 //node refere to the machaine that run the pipeline  there is two thing sccropted synatx and the decratlative synatx 