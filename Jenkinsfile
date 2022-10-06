pipeline 
{
    agent none
    stages 
	{
        stage('Build Stage')
		{
           		agent any
            		steps 
			{
				echo 'This is Build part'
			
				sh 'python app.py'
				
            		}
            	
        	}
        
    	}
}