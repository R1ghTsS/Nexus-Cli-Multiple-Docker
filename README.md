# Download this repo.
    git clone https://github.com/R1ghTsS/Nexus-Cli-Multiple-Docker.git && cd Nexus-Cli-Multiple-Docker
# Install nexus
    sed -i 's/\r$//' nexus.sh && chmod +x nexus.sh && ./nexus.sh
# If working (mining) fine, ctrl P + Q to exit
# If you are using termius ctrl P+Q will not work so change the shortcut key of ctrl + P in the settings of termius.
# To run the 2nd instance, 3rd instance ...
    ./nexus.sh
