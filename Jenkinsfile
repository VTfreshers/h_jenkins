pipeline
{
	agent any
		stages
		{
			stage ("fetch")
			{
				steps
				{
					ssh echo 'fetching code'
				}
			}
			stage ("build")
			{
				steps
				{
					ssh echo 'building code'
				}
			}
			stage ("test")
			{
				steps
				{
					ssh echo 'testing code'
				}
			}
		}
}
