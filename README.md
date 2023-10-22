# docker run busybox ls
# docker run busybox echo ‘bye there’
# docker run busybox ping google.com

# Create an image: docker create hello-world
# Run an image: docker start -a $imageId == docker start $imageId & docker logs $imageId
# To see all images: docker ps --all 
# To see running images: docker ps
# To remove all stopped images: docker system prune
# To stop running image: docker stop $imageId (nicely stop with some cleanup internally) or docker kill $imageId (instantly kill)
# Executing image in running containers: docker exec -it $imageId $container (docker exec -it busybox sh) to stop shell system using ctrl+d
# building a dockerfile: docker build . 
# run a docker file:docker run #fileId

