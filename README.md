# Litegraph App Example

This project is a custom application built using the LiteGraph library. It allows users to create and manipulate graphs with custom nodes for various operations, including multiplication and visual data processing. In detail, refer to [Visual Flow Programming](https://daddynkidsmakers.blogspot.com/2021/05/nodejs-visual-flow-programming.html)
<img src="https://github.com/mac999/litegraph-example/blob/main/img1.PNG?raw=true"></img>

## Description

The application provides a graphical interface for creating and managing nodes in a graph. It includes custom nodes such as `custom_multi_node` for multiplication and `custom_visual_data` for visual data processing. Users can interact with the graph through a canvas and control the execution of the graph using buttons.

## Installation

1. Clone the repository:
    ```sh
    git clone <repository-url>
    cd litegraph-server
    ```

2. Open the project directory:
    ```sh
    cd litegraph-server
    ```

3. Ensure you have a local server to serve the HTML file. You can use a simple HTTP server like `http-server`:
    ```sh
    npm install -g http-server
    ```
    
## Running the Application

1. Start the server:
    ```sh
    http-server
    ```

2. Open your browser and navigate to `http://localhost:8080` (or the port specified by your server).

## Usage

- **Run**: Starts the graph execution.
- **Stop**: Stops the graph execution.
- **Load Sound Graph**: Loads a predefined sound graph from `audio_delay.json`.
- **Save Graph JSON**: Saves the current graph configuration to `saved_graph.json`.
- **Load Graph JSON**: Loads a graph configuration from `saved_graph.json`.

## Author

- **Taewook Kang**: laputa99999@gmail.com

## References

- [LiteGraph Library](https://github.com/jagenjo/litegraph.js)

## License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.
