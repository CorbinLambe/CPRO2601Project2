REQUIRMENTS:
Docker desktop,
AWS SAM CLI

INSTRUCTIONS:
1. docker compose up -d		
2. docker compose ps             	
3. curl -s -o /dev/null -w "%{http_code}\n" http://localhost:8080  
4. docker compose down		
5. cd local-fn				
6. sam local invoke HelloWorldFunction 
7. cd ..
