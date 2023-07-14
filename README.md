# Proxy_Server

# Python TCP Port Forwarding

This Python script allows TCP port forwarding between a local server and a remote server. It listens for incoming connections on a specified port and forwards the data to the remote server.

## Usage

1. Modify the `forward_to` variable in the script to specify the remote server address and port.
2. Run the script using the command: `python port_forwarding.py`
3. The script will start listening for incoming connections on the specified port.

## Requirements

- Python 3.x

## How it works

The script utilizes the `socket` and `select` modules to establish connections and handle data transfer. It creates a server socket that listens for incoming connections. When a client connects, it establishes a connection with the remote server and creates a bidirectional channel for forwarding data.

## Configuration

You can customize the following parameters in the script:

- `buffer_size`: The buffer size for data transfer.
- `delay`: The delay between each data transfer.
- `forward_to`: The remote server address and port to forward data to.

## Contributions

Contributions are welcome! If you find any issues or have suggestions for improvements, please feel free to open an issue or submit a pull request.

## License

This project is licensed under the [MIT License](LICENSE).
