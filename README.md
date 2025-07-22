<img width="200" height="200" alt="Gemini_Generated_Image_buixpbuixpbuixpb" src="https://github.com/user-attachments/assets/5f2afaac-7a53-404a-bad9-daf1aaa8fed0" />

# PDida
A selected collection of Puredata abstractions for generative music.

This is a selection of objects/abstractions from rr_Libs to use in algorithmic composition.
Each object is accompanied by a help_patch_file which represents an example of how the abstraction works.

# Pdida Library for Pure Data
Welcome to the Pdida library, a collection of custom objects and abstractions for Pure Data (Pd). Developed to extend Pd's capabilities in the fields of electronic music, audio synthesis, and generative applications, this library aims to provide unique and powerful tools for musicians, sound designers, and programmers.
Pure Data is a real-time graphical programming environment for audio and video processing, created by Miller Puckette. It is free and open-source software, meaning its source code can be studied, modified, and redistributed by anyone. This philosophy of sharing and openness is also at the heart of the Pdida library.

# 🚀 Key Features
The Pdida library offers a wide range of objects and abstractions, all easily recognizable by the prefix rr_. These components are designed to expand Pure Data's capabilities, with a particular focus on generative music, advanced audio synthesis, and real-time signal control and manipulation tools.
Among the functionalities and objects you will find in the Pdida library:

## Synthesis and Sound Generation: 
Objects such as rr_pulsa+ (for rhythmic or sound impulse generation), rr_fm3/rr_fm4 (for advanced frequency modulation synthesis), rr_K+~ (for plucked string sound simulations, based on the Karplus-Strong principle). You can find more details on general FM concepts in the sources.

## Audio Signal Processing:
Includes effects like rr_echo~ (for creating echoes and delays), rr_mix~ (for mixing and manipulating audio signals), and rr_clamp~ (for signal limiting). Delays are fundamental in Pd for various purposes, including comb filters and reverberation.

## Generative and Algorithmic Music:
Many objects are dedicated to creating complex musical structures and emergent behaviors. Among these, rr_ratio, rr_brownian, rr_pendula, rr_chain, rr_meloga, rr_marki, and rr_serial allow for the exploration of algorithms and generative processes for unique compositions and performances. Other generative objects include rr_active/active+, rr_allchords, rr_allscales, rr_arpa+, rr_average, rr_ca8, rr_canon, rr_chordmelody, rr_chrd+, rr_combina, rr_contour, rr_cookies, rr_cosmelo, rr_cycles, rr_ddetune, rr_domina, rr_drunk, rr_dura2/mirdura2, rr_fefm, rr_glass, rr_harris, rr_intonation, rr_jumpli, rr_learning, rr_linear, rr_lolo~, rr_mappa, rr_mappa+, rr_mapPitch, rr_mediant, rr_melines, rr_mmeline, rr_modela, rr_motiva, rr_m-voice/t-voice, rr_noixe, rr_note6, rr_ostinato, rr_pad, rr_parametrizer, rr_pkbdp, rr_phrases, rr_quanta, rr_R8+, rr_res, rr_rgba, rr_satie, rr_scaling+, rr_sequi, rr_seqInt, rr_seqtrg, rr_smootha, rr_stira~, rr_stretch, rr_stretcha, rr_synthbrass/tremo, rr_synthr~, rr_tile/trillo~, rr_timbra~/tremo~, rr_tone~, rr_tonnetz, rr_toya, rr_trga, rr_voss, rr_wsha4~/wsha4, rr_xnoisa.

## Utilities and Control:
Essential tools are provided, such as rr_OUTdac~ (for managing the main audio output, similar to Pd's native dac~ object), rr_record~ (for recording performances), rr_adsr (a complete ADSR envelope generator) and rr_trga (for trigger and gate management, which can be achieved in Pd using objects like trigger or t).

# ⚙️ Installation and Usage

Clone or Download: You can clone this GitHub repository or download the ZIP archive directly.

Place the Library: After downloading the library, place the "Pdida" folder in one of the directories that Pure Data scans for external libraries. Typically, this can be in the same directory as the patch you are working on, or in one of the directories specified in Pure Data's "Path" menu.

Load in Pure Data: To ensure Pure Data loads the library on startup, you can add its directory to the "Path" (File > Path) or "Startup" (File > Startup) in the Pd window. Many versions of Pure Data (like Pd-extended, although less recent, or modern installations using Deken) simplify library management.
Once installed, you can use Pdida objects in your Pure Data patches just like any other native object, by typing their full name (e.g., rr_pulsa, rr_echo~, rr_fm~) in an "object box". Objects processing audio signals in Pd typically end with a tilde (~), and their inlets and outlets are dark.
