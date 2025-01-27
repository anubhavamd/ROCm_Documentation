==========================
HIP API Documentation v4.3
==========================

HIP API Guide 
---------------

You can access the latest Doxygen-generated HIP API Guide at the following location:

https://github.com/RadeonOpenCompute/ROCm/blob/master/AMD_HIP_API_Guide_v4.3.pdf


Supported CUDA APIs
--------------------

To access the following supported CUDA APIs, see

https://rocmdocs.amd.com/en/latest/Programming_Guides/Programming-Guides.html#hip-faq-porting-guide-and-programming-guide

* Runtime API

* Driver API

* cuComplex API

* cuBLAS

* cuRAND

* cuDNN

* cuFFT

* cuSPARSE


Deprecated HIP APIs
-------------------

HIP Context Management APIs
=============================

CUDA supports cuCtx API, the Driver API that defines "Context" and "Devices" as separate entities. Contexts contain a single device, and a device can theoretically have multiple contexts. HIP initially added limited support for APIs to facilitate easy porting from existing driver codes. The APIs are marked as deprecated now as there is a better alternate interface (such as hipSetDevice or the stream API) to achieve the required functions.

* hipCtxPopCurrent

* hipCtxPushCurrent

* hipCtxSetCurrent

* hipCtxGetCurrent

* hipCtxGetDevice

* hipCtxGetApiVersion

* hipCtxGetCacheConfig

* hipCtxSetCacheConfig

* hipCtxSetSharedMemConfig

* hipCtxGetSharedMemConfig

* hipCtxSynchronize

* hipCtxGetFlags

* hipCtxEnablePeerAccess

* hipCtxDisablePeerAccess



Related Topics
---------------

HIP Programming Guide 
======================

For the latest HIP Programming Guide, see

https://github.com/RadeonOpenCompute/ROCm/blob/master/AMD_HIP_Programming_Guide_v4.3.pdf


============================================
HIP-Supported CUDA API Reference Guide v4.3
============================================

You can access the latest HIP-Supported CUDA API Reference Guide at

https://github.com/RadeonOpenCompute/ROCm/blob/master/AMD_HIP_Supported_CUDA_API_Reference_Guide_v4.3.pdf

====================================
AMD ROCm Compiler Reference Guide
====================================

You can access and download the AMD ROCm Compiler Reference Guide at,

https://github.com/RadeonOpenCompute/ROCm/blob/master/AMD_Compiler_Reference_Guide_v4.3.pdf


   
 
==========================
OpenCL Programming Guide
==========================

* :ref:`Opencl-Programming-Guide`

OpenCL Best Practices
######################

* :ref:`Optimization-Opencl`


   

   

