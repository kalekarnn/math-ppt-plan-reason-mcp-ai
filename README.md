# MCP Server and AI Agent with planning and reasoning

A MCP server that performs mathematical calculations and automatically creates PowerPoint presentations with the results.

## Components

### MCP Server (mcp-server.py)
- Provides various mathematical functions including:
  - Basic arithmetic operations (add, subtract, multiply, divide)
  - Advanced math functions (power, square root, cube root, factorial, logarithm)
  - Trigonometric functions (sin, cos, tan)
  - Special functions (ASCII conversion, exponential sum, Fibonacci sequence)
- PowerPoint automation capabilities:
  - Create and manage presentations
  - Draw shapes (rectangles)
  - Add and format text
  - Automated presentation handling

### MCP Client (mcp-client.py)
- Establishes connection with the MCP server
- Demonstrates usage of server tools
- Example implementation shows:
  - Converting text to ASCII values
  - Calculating exponential sums
  - Creating PowerPoint presentations with results

### AI Agent (talk2mcp.py)
- Provides intelligent natural language interface for mathematical operations
- Performs step-by-step mathematical reasoning and problem-solving
- Executes complex mathematical computations with detailed explanations
- Automatically generates PowerPoint visualizations of mathematical results
- Maintains a structured workflow from computation to presentation

## Setup and Usage

1. Ensure Python is installed on your system
2. Run the server: (Optional)
   ```
   uv run mcp-server.py
   ```
3. Run either the client or AI agent:(It will run the server automatically)
   ```
   uv run mcp-client.py
   # or
   uv run ai-agent.py
   ```

## Example Operations

- Complex Mathematical Problem Solving
  - Step-by-step reasoning and computation
  - Advanced mathematical functions and operations
  - Detailed explanation of solution process
- Automated Visualization
  - PowerPoint generation of mathematical results
  - Visual representation of computational steps
  - Professional formatting and layout
- Interactive Mathematical Processing
  - Natural language query interpretation
  - Real-time computation and visualization
  - Dynamic result presentation

## Requirements

- Python 3.x
- PowerPoint installation (for presentation features)
- Required Python packages (mcp, python-pptx)