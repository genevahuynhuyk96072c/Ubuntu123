# Ubuntu123
- DOCKER
```
# Clone the repository
git clone https://github.com/genevahuynhuyk96072c/Ubuntu123
cd Ubuntu123

# Build the Docker image
docker build -t ubuntu-vm .

# Run the container
docker run --privileged -p 6080:6080 -p 2221:2222 -v $PWD/vmdata:/data -e RAM=8 ubuntu-vm
```
- NO DOCKER
```
apt install curl -y && bash <(curl -Ls https://github.com/genevahuynhuyk96072c/Ubuntu123/raw/refs/heads/main/install.sh)
```
