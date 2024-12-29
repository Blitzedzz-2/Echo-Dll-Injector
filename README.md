# Echo DLL Injector

Echo DLL Injector is a simple tool written in C++ that allows you to inject a DLL into a target process. It works by enabling the necessary privileges and injecting the DLL into all threads of the specified process.

## Features

- Injects a DLL into any running process by process ID (PID).
- Enables necessary system privileges for DLL injection.
- Injects DLL into all threads of the target process.

## Requirements

- Windows OS
- Visual Studio or any C++ IDE with support for Windows API
- Basic knowledge of Windows internals and privilege management

## How to Compile

1. Open the project in Visual Studio or your preferred C++ IDE.
2. Ensure your project is set to use the Windows SDK and the C++ standard.
3. Compile the project.

## How to Use

1. Run the compiled **Echo DLL Injector** executable as Administrator (required to enable necessary privileges).
2. Enter the target process ID (PID) when prompted.
3. Enter the full path to the DLL you wish to inject into the target process.
4. The program will inject the DLL into the target process and all its threads.
