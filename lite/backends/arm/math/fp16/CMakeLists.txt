cc_library(math_arm_fp16 SRCS
    conv_impl_fp16.cc
    gemm_fp16.cc
    gemv_fp16.cc
    conv3x3s1_depthwise_fp16.cc
    conv3x3s2_depthwise_fp16.cc
    conv3x3s1_depthwise_relu_fp16.cc
    conv3x3s2_depthwise_relu_fp16.cc
    DEPS ${lite_kernel_deps} context tensor)
