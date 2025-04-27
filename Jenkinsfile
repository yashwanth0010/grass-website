pipeline
{
    agent any
    
        stages
        {
            stage("Intializing")
            {
                steps
                {
                echo "Installing linux and hugo"
                }   
                
            }
            stage("Building")
            {
                steps
                {
                    echo "In Building stage"
                    powershell 'ls'

                    
                }
            }
            stage("Running")
            {
                steps
                {
                    powershell 'choco install hugo-extended'
                    powershell 'hugo server'
                }
            }
        }

    
}