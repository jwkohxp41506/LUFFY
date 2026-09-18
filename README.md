import base64

with open('/workspace/dumps/workspace/LUFFY/README.md', 'r') as f:
    content = f.read()

print(base64.b64encode(content.encode()).decode())