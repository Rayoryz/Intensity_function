# Intensity_function
# single-slit diffraction experiment

clear all; clc
maxCount = 10; % number of points
for (count = 1:maxCount)
x(count) = maxCount/2-count; % counting x value
y(count) = (sin(x(count))/x(count))^2; % function
fprintf('x= %+2.2f y= %+1.3f\n', x(count), y(count)); % Display output
end
