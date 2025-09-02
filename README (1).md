# LuminaCode Deployment

This repository contains deployment configurations for the LuminaCode API and Vector Database services. It supports one-click deployment to both Railway and Render platforms.

## 🚀 Quick Deploy

Choose your preferred platform:

### Railway
[![Deploy on Railway](https://railway.app/button.svg)](https://railway.app/new/template?template=https://github.com/wolater13-art/luminacode-deployment&plugins=postgresql)

### Render
[![Deploy to Render](https://render.com/images/deploy-to-render-button.svg)](https://render.com/deploy)

## 📋 Services

This deployment includes:
1. LuminaCode API - A FastAPI-based service
2. Vector Database - Qdrant vector database for efficient similarity search

## 🛠️ Configuration Files

- `railway.json` - Configuration for Railway deployment
- `render.yaml` - Configuration for Render deployment
- `Dockerfile` - Container configuration (required for both platforms)

## 📦 Requirements

- Docker support
- Python 3.8+
- FastAPI
- Qdrant

## 🔧 Environment Variables

- `WORKERS`: 4 (default)
- `PORT`: Automatically set by the platform

## 📚 Documentation

For more detailed information about deploying and configuring these services, please refer to:
- [Railway Documentation](https://docs.railway.app/)
- [Render Documentation](https://render.com/docs)