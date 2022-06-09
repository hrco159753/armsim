cmake_minimum_required(VERSION 3.0)

project(ArmSim LANGUAGES CXX)

add_executable(main)
target_sources(main
	PRIVATE
		main.cpp
)

