cmake_minimum_required(VERSION 2.6)
find_package(Rock)
rock_init(motoman_mh12 0.1)

install(FILES MH12_B2.wrl
             MH12_Base2.wrl
             MH12_L2.wrl
             MH12_R2.wrl
             MH12_S2.wrl
             MH12_T2.wrl
             MH12_U2.wrl
             motoman_mh122p.xml
       DESTINATION share/robots/motoman_mh12)      
