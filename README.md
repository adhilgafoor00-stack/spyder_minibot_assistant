# Spyder MiniBot Assistant

**MiniBot** is a concept for a small, friendly desktop robot inspired by expressive companion robots such as EMO. The goal is to combine a lively personality with practical assistance: MiniBot should interact with its owner, help with everyday computer tasks, and control supported smart-home devices.

> This repository is an early-stage project. The features below describe the intended direction and should not be read as already implemented.

## Vision

Build a personal robot assistant that can:

- Show expressions and respond naturally to voice, touch, or other supported inputs.
- Help the owner with tasks on their computer, with clear user approval for sensitive actions.
- Control connected home devices such as lights and fans through supported smart-home integrations.
- Provide useful status updates and respond to simple questions.

## Planned capabilities

### Companion robot

- Friendly character, expressions, and conversational interaction.
- Voice input and spoken responses, depending on the hardware and software available.
- A modular design so sensors, display, speakers, and other components can be added over time.

### Smart-home control

- Turn compatible lights and fans on or off.
- Support additional devices and actions as integrations are added.
- Confirm commands and report when a device is unavailable.

Home control requires compatible devices, a supported hub or platform, network access, and secure configuration. MiniBot should only control devices the owner has explicitly connected and authorized.

### Computer assistance

- Help with common tasks on the owner's computer, such as opening apps or finding information.
- Use explicit confirmation before actions that could change files, settings, or accounts.
- Keep the owner informed about what it is doing.

Computer access depends on the operating system, permissions, and integrations that are implemented. No feature should be assumed available until documented and tested in this repository.

## Project status

**Status: early-stage / under development.**

The repository is being set up for the MiniBot Assistant project. Implementation details, supported hardware, installation steps, and working features will be documented here as they become available.

## Getting started

There are no installation or run instructions yet. They will be added when the initial implementation and supported hardware/software requirements are established.

## Roadmap

- [ ] Define the robot hardware and supported computer platform.
- [ ] Create the initial assistant and interaction architecture.
- [ ] Add voice input and response.
- [ ] Integrate a supported smart-home platform for lights and fans.
- [ ] Add safe computer-assistance tools with user confirmation.
- [ ] Document installation, configuration, and troubleshooting.

## Safety and privacy

- Protect access credentials and device tokens; never commit secrets to the repository.
- Require owner authorization before connecting or controlling devices.
- Use confirmation for sensitive computer actions.
- Explain what data is processed and where it is stored once those details are implemented.

## Contributing

This project is at an early stage. Suggestions and contributions are welcome. Please open an issue to discuss a feature or hardware integration before starting a large change.

## License

No license has been specified yet. Until one is added, reuse and redistribution are not granted by this README.
