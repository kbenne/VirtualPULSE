VirtualPULSE
============

HUB VirtualPULSE Project
 
Installation instructions (Windows)

0. Download EnergyPlus 7.1.0 from http://apps1.eere.energy.gov/buildings/energyplus/
1. Download & Install Ruby 1.8.7 from http://rubyinstaller.org/
2. Download & Install OpenStudio 0.8.1 from http://openstudio.nrel.gov/downloads
3. Create a BCL API key - follow instructions here:  https://openstudio.nrel.gov/using-building-component-library-bcl-key-openstudio

Running the script

1. start->run->cmd
2. in the command prompt: cd directory_where_virtualpulse_repo_lives
3. in the command prompt: ruby VirtualPULSE_run.rb

This should create a file called exampleVirtualPULSEModel.osm in the VirtualPULSE directory.

4. if you want to run the simulation, in VirtualPULSE_run.rb, at the end, change 


      
