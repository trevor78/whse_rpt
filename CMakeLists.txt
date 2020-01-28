cmake_minimum_required(VERSION 2.6)
project(whse_rcpt)
add_executable(	whse_rcpt whse_rcpt.c)
target_link_libraries( whse_rcpt whse_lib)
