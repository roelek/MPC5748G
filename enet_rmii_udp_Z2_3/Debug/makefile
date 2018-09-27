################################################################################
# Automatically-generated file. Do not edit!
################################################################################

#Progress monitor hint: 6
first : all
-include ../makefile.init

# This file contains definitions of environment variables used in the makefiles and .args files if exist.
-include makefile.local

RM := rm -rf

# All of the sources participating in the build are defined here
-include sources.mk
-include subdir.mk
-include Project_Settings/Linker_Files/subdir.mk
-include Project_Settings/Startup_Code/subdir.mk
-include src/subdir.mk
-include objects.mk

ifneq ($(MAKECMDGOALS),clean)
ifneq ($(strip $(C_DEPS)),)
-include $(C_DEPS)
endif
endif

-include ../makefile.defs

# Add inputs and outputs from these tool invocations to the build variables 
EXECUTABLES += \
enet_rmii_udp_Z2_3.elf \

EXECUTABLES_QUOTED += \
"enet_rmii_udp_Z2_3.elf" \

EXECUTABLES_OS_FORMAT += \
enet_rmii_udp_Z2_3.elf \


# All Target
all: warning-messages explicit-dependencies enet_rmii_udp_Z2_3.elf secondary-outputs

# Tool invocations
enet_rmii_udp_Z2_3.elf: $(OBJS) D:/Workspace/Projekte/RO\ -\ Elektronik\ GmbH/SW/Neuer\ Ordner/DEVKIT-MPC5748G_Rev-B_Code_Examples/enet_rmii_udp/enet_rmii_udp_Z2_3/Project_Settings/Linker_Files/mem.ld D:/Workspace/Projekte/RO\ -\ Elektronik\ GmbH/SW/Neuer\ Ordner/DEVKIT-MPC5748G_Rev-B_Code_Examples/enet_rmii_udp/enet_rmii_udp_Z2_3/Project_Settings/Linker_Files/sections.ld D:/Workspace/Projekte/RO\ -\ Elektronik\ GmbH/SW/Neuer\ Ordner/DEVKIT-MPC5748G_Rev-B_Code_Examples/enet_rmii_udp/enet_rmii_udp_Z2_3/Project_Settings/Linker_Files/libs.ld $(OSPT) $(USER_OBJS)
	@echo 'Building target: $@'
	@echo 'Executing target #7 $@'
	@echo 'Invoking: Standard S32DS C Linker'
	powerpc-eabivle-gcc -o "enet_rmii_udp_Z2_3.elf" "@enet_rmii_udp_Z2_3.args"  $(USER_OBJS_QUOTED) $(LIBS_QUOTED) $(OSPT)
	@echo 'Finished building target: $@'
	@echo ' '

# Other Targets
clean:
	-$(RM) ./*/*.d  ./*/*.o ./*/*/*.o  $(EXECUTABLES_QUOTED)
	-@echo ' '

secondary-outputs:

.PHONY: all clean dependents explicit-dependencies warning-messages
.SECONDARY:

-include ../makefile.targets

explicit-dependencies: 

warning-messages: 

