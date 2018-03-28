cmake_minimum_required(VERSION 3.9)
project(ARA_reconstruction)

set(CMAKE_CXX_STANDARD 11)

add_executable(ARA_reconstruction
        analysis.cxx
        analysis_2015DeepPulser.cxx
        analysis_2017DeepPulser.cxx
        analysis_angle.cxx
        analysis_anotherPol.cxx
        analysis_constantNFilter.cxx
        analysis_treg.cxx
        calibrationTools.cxx
        calibrationTools.h
        calibrationToolsVs3.cxx
        calibrationToolsVs3.h
        evProcessTools.cxx
        evProcessTools.h
        Healpix_Onion.cxx
        Healpix_Onion.h
        kernel_3D_analysis.c
        linkdef_recoData.h
        linkdef_recoSettings.h
        linkdef_trackEngine.h
        recoData.cxx
        recoData.h
        recoSettings.cxx
        recoSettings.h
        recoTools.cxx
        recoTools.h
        trackEngine.cxx
        trackEngine.h
        treg.cxx)
