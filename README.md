# LaserMicEENG3920
Spring 25' UNT EENG 3920 Final Project

A laser microphone is a device that remotely detects sound vibrations by using a laser beam reflected off a surface. Instead of picking up sound waves directly through air like traditional microphones, it captures minute surface vibrations caused by sound. These vibrations modulate the reflected laser light, and through optical and electronic processing, the variations are translated back into an audio signal.

Originally developed for espionage and surveillance in the mid-20th century, laser microphones provided a method to eavesdrop from a significant distance without physical access to the target area. Early examples, such as devices used during the Cold War, demonstrated the strategic advantage of remote listening technologies.

A laser is aimed at a reflective surface—such as a window, picture frame, or even a plastic object—that vibrates with nearby sounds. Subtle movements cause detectable changes in the phase or path of the reflected beam. Sensors convert these changes into electrical signals, which are then processed into intelligible sound.

Today, laser microphones find use beyond surveillance, including in scientific research, industrial monitoring, and medical diagnostics, offering a non-invasive way to capture acoustic information from environments that would otherwise be inaccessible.

we used a combination of different references to adjust our circuit for audio jack output. we used videos and other projects to fill the learning curve of implementing a laser microphone embedded system on the STM32. The STM 32 was intended to use an sd card reader to read a .wav file and output the signal to a speaker in our circuit. The STM32 is using SPI interfacing with FatFS. Our project focuses on ADC, demodulation, amplification and filtering of a "message" signal.  
