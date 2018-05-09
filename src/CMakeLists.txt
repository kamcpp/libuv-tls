cmake_minimum_required (VERSION 2.8.11)
project(uv-tls)

add_library(uv-tls SHARED
  uv_tls.c
  tls_engine.c
)
