IOC_TOP = /reg/g/pcds/epics/ioc/common/ads-ioc/R0.6.2
IOC_INSTANCE_PATH := $(shell pwd)

# Set PRODUCTION_IOC to 1 to move from a testing to a production IOC:
PRODUCTION_IOC := 1

PROJECT_NAME := Arbiter
PROJECT_PATH := ../../Arbiter/Arbiter.tsproj
PLC := KFEArbiter

PYTMC_OPTS := 
PREFIX := PMPS:KFE

include $(IOC_TOP)/iocBoot/templates/Makefile.base
