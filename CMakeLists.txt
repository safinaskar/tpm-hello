cmake_minimum_required (VERSION 3.0.2) # 3.0.2 подходит
project (tpm-hello LANGUAGES C)
add_executable (tpm-hello main.c)
install (TARGETS tpm-hello DESTINATION bin)
