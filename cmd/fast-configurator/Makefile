FAST_CONFIG_OUTPUT_DIR := ./
FAST_CONFIG_BUILD_DIR := ./
FAST_CONFIG_BINARY_NAME := fast-configurator

.PHONY: clean
clean:
	@echo "Cleaning up..."
	@rm -f $(FAST_CONFIG_OUTPUT_DIR)/$(FAST_CONFIG_BINARY_NAME)
	@echo "Clean complete."

.PHONY: build
build:
	@echo "Building fast-configurator..."
	@cd $(FAST_CONFIG_BUILD_DIR) && go build -o $(FAST_CONFIG_BINARY_NAME)
	@echo "Build complete. Binary is located at $(FAST_CONFIG_OUTPUT_DIR)/$(FAST_CONFIG_BINARY_NAME)"