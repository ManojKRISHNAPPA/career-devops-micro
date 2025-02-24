pipeline {
    agent any
    stages{
        stage('Build system details'){
            steps{
                sh ''' 
                echo "system details-1st stage"
                uname -a
                '''
            }
        }
        stage('memory-details'){
            steps{
               sh ''' 
                echo "printing memory-details"
                free -h
               ''' 
            }
        }
        stage('cpu details'){
            steps{
                sh '''
                echo "printing cpu-details"
                lscpu
                '''
            }
        }
        stage('date'){
            steps{
               sh '''
                echo "printing current date"
                date
                ''' 
            }
        }
        stage('current-process-running'){
            steps{
               sh '''
                echo "printing current-process-running"
                ps -eaf | head
                ''' 
            }
        }
      satge('diskspace'){
           steps{
             sh '''
echo "printing the diskspaace"
df -kh


'''
}
}


    }
} 


