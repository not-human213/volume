# Volume Adjustment Project 🎵  

## Features ✨  

- **Volume Adjustment:** Increase or decrease the volume of `.wav` audio files by a user-defined factor.  
- **Header Preservation:** Maintains the integrity of the `.wav` file header.  
- **Efficient Processing:** Processes audio samples iteratively for minimal memory usage.  

## Tools & Technologies 🛠  

- **Language:** C  
- **Input/Output Format:** `.wav` files  

## Getting Started 🚀  

### Prerequisites  

Ensure you have the following installed:  

- GCC or any C compiler  
- Make utility  

### Installation  

1. Clone this repository:  
   ```bash  
   git clone https://github.com/not-human213/volume.git
   cd volume  
2. Run the program:
   ```bash
   ./volume input.wav output.wav factor  

- Replace input.wav with the name of the input audio file.
- Replace output.wav with the desired name of the output audio file.
- Replace factor with a float value to scale the volume (e.g., 2.0 to double, 0.5 to halve).
