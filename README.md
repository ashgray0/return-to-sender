# return-to-sender
A 4-channel, CV/touch plate controlled "no-input mixer" for Eurorack.

"No-input mixing" is a primitive method of creating sound that's popular in the world of experimental noise music. By patching the main outputs of any audio mixer back into its individual inputs, irratic and unpredictable feedback loops are generated without the need for any external audio input (hence the name). These feedback loops can then be shaped by tweaking the level and EQ controls of the individual channels. The results can vary from physical pain to interesting, minimalist rhythms and textures that are impossible to replicate. Here is an example of the latter: https://www.youtube.com/watch?v=MxM98JI44OQ.

The aim of this project is to make a Eurorack module that consists of an incredibly basic 4-channel mixer (the actually sound quality doesn't really matter here - we *want* noise and chaos!) which is pre-routed to create feedback on each of the channels. After being amplified and sent through a basic 1-knob tone circuit (the tone circuit from the Big Muff Pi fuzz pedal - it should be ideal here since it is extremely simple, has a dramatic effect on the signal, and is designed for use in a high-gain context), each channel is then sent to a VCA, after which the outputs are mixed and the mixed signal is routed back to the inputs. 

Each of the 4 VCAs is controlled by a capactive touch plate. Since small parameter changes tend to result in non-linear, chaotic responses in the feedback loops, small changes in pressure applied to the touch plates should create a highly expressive performance interface. Alternatively, the VCAs can also be controlled by CV inputs. 

The schematic in this repository is just a basic outline of the concept I put together one night recently (after watching a bunch of no-input mixing performance videos on YouTube and having the initial idea). 
