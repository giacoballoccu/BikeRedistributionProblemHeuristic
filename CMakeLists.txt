cmake_minimum_required(VERSION 3.17)
project(PSO_BSRP)

set(CMAKE_CXX_STANDARD 14)

add_executable(PSO_BSRP main.cpp BikeSharingRebalancingModel/BikeRebalancingModel.h BikeSharingRebalancingModel/BikeRebalancingModel.cpp BikeSharingRebalancingModel/Station.h BikeSharingRebalancingModel/Station.cpp BikeSharingRebalancingModel/Simulator.h BikeSharingRebalancingModel/Simulator.cpp BikeSharingRebalancingModel/Vehicle.h BikeSharingRebalancingModel/Vehicle.cpp PSOImplementation/PSOUtils.cpp PSOImplementation/PSOUtils.h PSOImplementation/Swarm.h PSOImplementation/Swarm.cpp PSOImplementation/Particle.h PSOImplementation/Particle.cpp)