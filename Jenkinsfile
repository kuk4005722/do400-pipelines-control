node('nodejs') 
{    
	stage('Checkout') 
	{        
		git branch: 'main',            
		url: 'https://github.com/kuk4005722/do400-pipelines-control'    }    

	stage('Backend Tests123') 
	{        
		sh 'node ./backend/test.js'    
	}    

	stage('Frontend Test3535') 
	{
		sh 'node ./frontend/test.js'    
	}
}
