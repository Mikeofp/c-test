# c-test

#include "mbed.h"
#include "libuopmsb.h"

int main() {
    // initialize the speaker
    uopmsb_speaker_init();

    // play the Doom main song using libuopmsb
    uopmsb_play_music("doom_main_song.bin");

    return 0;
}
