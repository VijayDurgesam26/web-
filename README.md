# Clone the repository or create a new one
mkdir taskmaster
cd taskmaster
git init
# Create frontend and backend directories
mkdir -p taskmaster-frontend taskmaster-backend/{gateway-service,auth-service,task-service,user-service}
