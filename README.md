# SensorFusion_Kalman_and_Particle_Filter

The project has 2 jupyter notebook files named with Kalman_Filter_Portfolio_2.ipynb , and Particle_Filter_Portfolio_2.ipynb. I have also added the python files as well in the folder.
you can open these files in your vscode or google colab or in  any of your fav IDE
To run this project you need to ensure to install these require pkgs in your environment

# Requirements
1. Python 3.x
2. NumPy
3. Matplotlib

you can install these libraries via pip or pip3 

# pip install Numpy
# pip install Matplotlib

# Parameters
# Kalman Filter 
1. launch_position: Initial position of the ball (e.g., [10, 10]).
2. launch_speed: Initial speed of the ball.
3. launch_angle: Launch angle in degrees.
4. time_step: Time step between observations.
5. total_time: Total simulation time.
6. observation_noise: Standard deviation of observation noise.
7. skip_observations: Boolean to simulate missing observations.
8. skip_ob_start_time: Start time to skip observations.
9. skip_ob_stop_time: Stop time to skip observations.
10. transition_cov_scale: Scale of the transition covariance matrix.

# Parameters 
# Particle Filter
1. num_particles: Number of particles in the filter.
2. initial_covariance_scale: Scale of the initial covariance matrix.
3. transition_cov_scale: Scale of the transition covariance matrix.
4. observation_noise: Standard deviation of observation noise.
5. skip_observations: Boolean to simulate missing observations.
6. skip_ob_start_time: Start time to skip observations.
7. skip_ob_stop_time: Stop time to skip observations.
