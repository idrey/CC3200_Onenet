################################################################################
# Automatically-generated file. Do not edit!
################################################################################

SHELL = cmd.exe

CG_TOOL_ROOT := D:/Software/ti/ccsv6/tools/compiler/ti-cgt-arm_15.12.1.LTS

GEN_OPTS__FLAG := 
GEN_CMDS__FLAG := 

ORDERED_OBJS += \
"./button_if.obj" \
"./cJSON.obj" \
"./gpio_if.obj" \
"./i2c_if.obj" \
"./main.obj" \
"./network_common.obj" \
"./network_if.obj" \
"./pinmux.obj" \
"./startup_ccs.obj" \
"./timer_if.obj" \
"./uart_if.obj" \
"../cc3200v1p32.cmd" \
$(GEN_CMDS__FLAG) \
-llibc.a \
-l"C:/TI/CC3200SDK_1.3.0/cc3200-sdk/oslib/ccs/free_rtos/free_rtos.a" \
-l"C:/TI/CC3200SDK_1.3.0/cc3200-sdk/simplelink/ccs/OS/simplelink.a" \
-l"C:/TI/CC3200SDK_1.3.0/cc3200-sdk/netapps/mqtt/ccs/client/mqtt.a" \
-l"C:/TI/CC3200SDK_1.3.0/cc3200-sdk/driverlib/ccs/Release/driverlib.a" \

-include ../makefile.init

RM := DEL /F
RMDIR := RMDIR /S/Q

# All of the sources participating in the build are defined here
-include sources.mk
-include subdir_vars.mk
-include subdir_rules.mk
-include objects.mk

ifneq ($(MAKECMDGOALS),clean)
ifneq ($(strip $(S_DEPS)),)
-include $(S_DEPS)
endif
ifneq ($(strip $(S_UPPER_DEPS)),)
-include $(S_UPPER_DEPS)
endif
ifneq ($(strip $(S62_DEPS)),)
-include $(S62_DEPS)
endif
ifneq ($(strip $(C64_DEPS)),)
-include $(C64_DEPS)
endif
ifneq ($(strip $(ASM_DEPS)),)
-include $(ASM_DEPS)
endif
ifneq ($(strip $(CC_DEPS)),)
-include $(CC_DEPS)
endif
ifneq ($(strip $(SV7A_DEPS)),)
-include $(SV7A_DEPS)
endif
ifneq ($(strip $(S55_DEPS)),)
-include $(S55_DEPS)
endif
ifneq ($(strip $(C67_DEPS)),)
-include $(C67_DEPS)
endif
ifneq ($(strip $(CLA_DEPS)),)
-include $(CLA_DEPS)
endif
ifneq ($(strip $(C??_DEPS)),)
-include $(C??_DEPS)
endif
ifneq ($(strip $(CPP_DEPS)),)
-include $(CPP_DEPS)
endif
ifneq ($(strip $(S??_DEPS)),)
-include $(S??_DEPS)
endif
ifneq ($(strip $(C_DEPS)),)
-include $(C_DEPS)
endif
ifneq ($(strip $(C62_DEPS)),)
-include $(C62_DEPS)
endif
ifneq ($(strip $(CXX_DEPS)),)
-include $(CXX_DEPS)
endif
ifneq ($(strip $(C++_DEPS)),)
-include $(C++_DEPS)
endif
ifneq ($(strip $(ASM_UPPER_DEPS)),)
-include $(ASM_UPPER_DEPS)
endif
ifneq ($(strip $(K_DEPS)),)
-include $(K_DEPS)
endif
ifneq ($(strip $(C43_DEPS)),)
-include $(C43_DEPS)
endif
ifneq ($(strip $(INO_DEPS)),)
-include $(INO_DEPS)
endif
ifneq ($(strip $(S67_DEPS)),)
-include $(S67_DEPS)
endif
ifneq ($(strip $(SA_DEPS)),)
-include $(SA_DEPS)
endif
ifneq ($(strip $(S43_DEPS)),)
-include $(S43_DEPS)
endif
ifneq ($(strip $(OPT_DEPS)),)
-include $(OPT_DEPS)
endif
ifneq ($(strip $(PDE_DEPS)),)
-include $(PDE_DEPS)
endif
ifneq ($(strip $(S64_DEPS)),)
-include $(S64_DEPS)
endif
ifneq ($(strip $(C_UPPER_DEPS)),)
-include $(C_UPPER_DEPS)
endif
ifneq ($(strip $(C55_DEPS)),)
-include $(C55_DEPS)
endif
endif

-include ../makefile.defs

# Add inputs and outputs from these tool invocations to the build variables 
EXE_OUTPUTS += \
mqtt_client.out \

EXE_OUTPUTS__QUOTED += \
"mqtt_client.out" \

BIN_OUTPUTS += \
mqtt_client.bin \

BIN_OUTPUTS__QUOTED += \
"mqtt_client.bin" \


# All Target
all: mqtt_client.out

# Tool invocations
mqtt_client.out: $(OBJS) $(CMD_SRCS) $(GEN_CMDS)
	@echo 'Building target: $@'
	@echo 'Invoking: ARM Linker'
	"D:/Software/ti/ccsv6/tools/compiler/ti-cgt-arm_15.12.1.LTS/bin/armcl" -mv7M4 --code_state=16 --float_support=fpalib -me -g --gcc --define=ccs --define=USE_FREERTOS --define=SL_PLATFORM_MULTI_THREADED --define=cc3200 --diag_wrap=off --diag_warning=225 --display_error_number --abi=eabi -z -m"mqtt_client.map" --stack_size=0x5000 --heap_size=0x8000 -i"D:/Software/ti/ccsv6/tools/compiler/ti-cgt-arm_15.12.1.LTS/lib" -i"D:/Software/ti/ccsv6/tools/compiler/ti-cgt-arm_15.12.1.LTS/include" --reread_libs --display_error_number --warn_sections --diag_wrap=off --xml_link_info="mqtt_client_linkInfo.xml" --rom_model -o "mqtt_client.out" $(ORDERED_OBJS)
	@echo 'Finished building target: $@'
	@echo ' '
	@$(MAKE) --no-print-directory post-build

mqtt_client.bin: $(EXE_OUTPUTS)
	@echo 'Invoking: ARM Hex Utility'
	"D:/Software/ti/ccsv6/tools/compiler/ti-cgt-arm_15.12.1.LTS/bin/armhex"  -o "mqtt_client.bin" $(EXE_OUTPUTS__QUOTED)
	@echo 'Finished building: $@'
	@echo ' '
	@$(MAKE) --no-print-directory post-build

# Other Targets
clean:
	-$(RM) $(EXE_OUTPUTS__QUOTED)$(BIN_OUTPUTS__QUOTED)
	-$(RM) "button_if.d" "cJSON.d" "gpio_if.d" "i2c_if.d" "main.d" "network_common.d" "network_if.d" "pinmux.d" "startup_ccs.d" "timer_if.d" "uart_if.d" 
	-$(RM) "button_if.obj" "cJSON.obj" "gpio_if.obj" "i2c_if.obj" "main.obj" "network_common.obj" "network_if.obj" "pinmux.obj" "startup_ccs.obj" "timer_if.obj" "uart_if.obj" 
	-@echo 'Finished clean'
	-@echo ' '

post-build:
	-"D:/Software/ti/ccsv6/utils/tiobj2bin/tiobj2bin" "mqtt_client.out" "mqtt_client.bin" "D:/Software/ti/ccsv6/tools/compiler/ti-cgt-arm_15.12.1.LTS/bin/armofd" "D:/Software/ti/ccsv6/tools/compiler/ti-cgt-arm_15.12.1.LTS/bin/armhex" "D:/Software/ti/ccsv6/utils/tiobj2bin/mkhex4bin"
	-@echo ' '

.PHONY: all clean dependents
.SECONDARY: post-build

-include ../makefile.targets

