Dependencies:

    sudo apt-get install nasm bochs bochs-sdl bochsbios bochs-x g++

Setting up and running:

    cd src
    make clean
    make all
    cd ..
    ./update_image.sh
    ./run_bochs.sh