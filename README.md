# sudheer.yml
# Example of a simple YAML configuration file

# Defining a list of items
items:
  - name: "Item 1"
    type: "Type A"
    quantity: 10
  - name: "Item 2"
    type: "Type B"
    quantity: 5

# Defining a dictionary
settings:
  debug: true
  max_connections: 100
  timeout: 30

# Nested structures
server:
  address: "192.168.1.1"
  port: 8080
  ssl: true
  credentials:
    username: "admin"
    password: "securepassword"

# Multi-line string
description: |
  This is a multi-line string.
  It can span several lines.
  Indentation is important here.
