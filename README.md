# Medusa B2B Tutorial

This repository is the codebase of tutorial "How to Create B2B Store with Medusa" - specifically the Medusa server.

[Medusa Documentation](https://docs.medusajs.com/) | [Medusa Website](https://medusajs.com/) | [Medusa Repository](https://github.com/medusajs/medusa)

## Medusa Version

This tutorial uses Medusa v1.6.5. It is not guaranteed that it will work with future releases.

## Prerequisites

- [Node.js at least v14](https://docs.medusajs.com/tutorial/set-up-your-development-environment#nodejs)
- [PostgreSQL](https://docs.medusajs.com/tutorial/set-up-your-development-environment#postgresql)
- [Medusa CLI Tool](https://docs.medusajs.com/cli/reference)
- [MinIO](https://docs.medusajs.com/add-plugins/minio/#set-up-minio)

## How to Install

### Using Medusa CLI tool

1. Run the following command to install the Medusa server using Medusa's CLI tool:

```bash
medusa new b2b-server https://github.com/shahednasser/b2b-server
```

2\. Start Medusa Server:

```bash
cd b2b-server
npm start
```

### Using GitHub Repository

1. Clone this repository:

```bash
git clone https://github.com/shahednasser/b2b-server.git
cd b2b-server
```

2\. Install the dependencies:

```bash
npm install
```

3\. Rename the template environment variables of Medusa server:

```bash
mv .env.template .env
```

And enter the necessary environment variables in the file.

4\. Start Medusa Server:

```bash
npm start
```

## Other Resources

- [Medusa Documentation](https://docs.medusajs.com/)