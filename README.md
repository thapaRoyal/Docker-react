# Docker commands

#### docker build -t ecommerce-image .

#### docker stop ecommerce-container

#### docker ps

#### docker run --rm --name ecommerce-container -d -p 3000:3000 ecommerce-image

#### docker stop <container name or image>

#### docker run --rm --name ecommerce-container -d -p 3000:3000 -v $(pwd):/app ecommerce-image

#### docker logs efcdc4edd1ff

#### docker exec -it ecommerce-container bash
