FROM golang:1.16

# Copy the proxy code to the container.
COPY main.go .

# Run the proxy on container startup.
ENTRYPOINT [ "go" ]
CMD [ "run", "main.go" ]

# Expose the proxy port.
EXPOSE 8000