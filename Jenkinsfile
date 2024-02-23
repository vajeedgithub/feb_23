pipeline
	{
	agent any
		stages
			{
			stage("git")
					{
					steps
						{
						git "https://github.com/vajeedgithub/feb_23.git"
						}
					}
			stage("run")
				{
				steps
					{
					sh 'java demo.java'
					sh 'python3 main.py'
					}
				}
			}
 		}

			
