# Example Image Conversion Service

This is a simple service that receives a ByteArray-encoded image and returns a base64-encoded image.

It will be published as a process-type service (so we're not using GRPC or JSON: SNET Daemon communicates with the service via stdin/stdout).
