# Visualizing Packing in Matlab

% Load positions into x and diameters into D

data = load('Final.txt'); x = data(:,1:length(data(1,:))-1); D = data(:,length(data(1,:)));

plot_particles_3D(x, D, [4,4,250],5)

axis([0,4,0,4,0,14])

