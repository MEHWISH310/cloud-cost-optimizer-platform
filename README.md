# Cloud Cost Optimization and Service Model Comparison Platform

A web-based platform that helps organizations make informed decisions about cloud usage by comparing costs and features across different cloud service models (IaaS, PaaS, SaaS) and deployment models (Public, Private, Hybrid Cloud).

## About The Project

Cloud computing has changed the way storage, processing power, and software services are delivered over the internet. However, picking the right cloud service models and keeping operational costs under control is still a big problem. This platform bridges the gap between theoretical cloud concepts and real-world application by providing:

- Cost simulation and comparison across AWS, Azure, and GCP
- Educational content about service and deployment models
- Visual cost analysis with charts and tables
- Cloud cost optimization best practices

## Features

### 1. Cost Calculator
- Compute power selection (CPU, RAM, instances)
- Storage capacity input (GB/TB)
- Data transfer calculator
- Pay-as-you-go pricing simulation
- Monthly/yearly cost estimates

### 2. Multi-Cloud Comparison
- Compare prices across AWS, Azure, and GCP
- Side-by-side cost breakdown
- Provider-specific pricing data

### 3. Service Models Information
- **IaaS (Infrastructure as a Service)** - Explanation, examples, responsibility matrix
- **PaaS (Platform as a Service)** - Explanation, examples, responsibility matrix
- **SaaS (Software as a Service)** - Explanation, examples, responsibility matrix

### 4. Deployment Models Information
- **Public Cloud** - Use cases, benefits, limitations
- **Private Cloud** - Use cases, benefits, limitations
- **Hybrid Cloud** - Use cases, benefits, limitations

### 5. Visual Analytics
- Bar charts for price comparison
- Pie charts for cost breakdown
- Comparison tables
- Cost trend visualization

### 6. Optimization Tips
- Resource sizing recommendations
- Service selection guidance
- Deployment strategy tips
- Cost-saving best practices

## Tech Stack

- **Frontend:** React.js, Chart.js, CSS
- **Backend:** Node.js, Express
- **Data:** JSON/CSV (pricing data for AWS, Azure, GCP)
- **Deployment:** AWS/Azure/GCP + GitHub

## Getting Started

### Prerequisites
Make sure you have these installed on your system:
- **Node.js** (v14 or higher) - [Download here](https://nodejs.org)
- **Git** - [Download here](https://git-scm.com/downloads)
- **Code Editor** (VS Code)

### Installation Steps

#### 1. Clone the Repository
Open your terminal/command prompt and run:
```bash
git clone https://github.com/MEHWISH310/cloud-cost-optimizer-platform.git
cd cloud-cost-optimizer-platform
```

#### 2. Backend Setup
```bash
# Navigate to the backend directory (create it first if it doesn't exist)
mkdir backend
cd backend

# Initialize project and install dependencies
npm init -y
npm install express cors

# Create the main server file (e.g., server.js) and add your backend code
# For now, you can create a simple test server.

# Start the backend server
node server.js
```
The backend server will typically run on http://localhost:5000.

#### 3. Frontend Setup (React)
Open a new terminal window (keep the backend running) and navigate back to your project root, then into the frontend:
```bash
# From the project root
npx create-react-app frontend
cd frontend

# Install additional frontend dependencies
npm install axios chart.js react-chartjs-2

# Start the React development server
npm start
```
The frontend app will usually open automatically at http://localhost:3000.
#### 4. Verify the Setup
- Your backend API should be running on http://localhost:5000.
- Your frontend React app should be running on http://localhost:3000.
- The frontend should be configured to make API calls to the backend.
