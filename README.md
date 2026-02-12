# Install Payload

# Install Payload S3 Storage support

# Modify next.config.js

```
images: {
    remotePatterns: [
      {
        hostname: process.env.NEXT_PUBLIC_SERVER_URL.split('https://')[1],
        protocol: 'https',
      },
    ],
  },
```
