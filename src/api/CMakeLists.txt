# -*- mode: cmake; -*-


set(api_srcs
  Volkszaehler.cpp
  Emoncms.cpp
  MySmartGrid.cpp
  InfluxDB.cpp
  Null.cpp
  CurlIF.cpp
  CurlCallback.cpp
  CurlResponse.cpp
)

add_library(vz-api ${api_srcs})
