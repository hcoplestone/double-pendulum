[![Build Status](https://api.travis-ci.com/dassencio/double-pendulum.svg?branch=master)](https://travis-ci.com/dassencio/double-pendulum)

# Description

A double pendulum simulator (written in Python 3) which uses the Runge-Kutta
(RK) method to solve the set of differential equations from either the
[Lagrangian formulation](http://diego.assencio.com/?index=1500c66ae7ab27bb0106467c68feebc6)
or from the [Hamiltonian formulation](https://diego.assencio.com/?index=e5ac36fcb129ce95a61f8e8ce0572dbf)
for the double pendulum problem.

# License

All code from this project is licensed under the GPLv3. See the
[`LICENSE`](https://github.com/dassencio/double-pendulum/tree/master/LICENSE)
file for more information.

# Required modules

The following modules are used:

- `numpy`
- `pygame`

You can install them with the following command:

    pip3 install pygame numpy

# Usage instructions

Run `./double-pendulum -h` to get a list of simulation parameters which can
be set.

# Notes on stability

If your simulation becomes unstable, try doing one or more of the following:

- reduce the time step
- reduce the initial angular velocities
- reduce the gravitational acceleration

# Contributors & contact information

Diego Assencio / diego@assencio.com
