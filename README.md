# Serverless Enhancements for the Algonquin Pet Store (On Steroids)

# Youtube Demo: https://youtu.be/qKsV__Ua_Cg 

This repository contains a PowerPoint presentation that explores how serverless computing concepts can be applied to refactor and enhance the **Algonquin Pet Store (On Steroids)** application.

## 📑 Contents
- `Serverless_Pet_Store_with_Diagram.pptx`  
  The presentation slides with speaker notes and an embedded system architecture diagram.

## 🎯 Objective
The purpose of this presentation is to demonstrate the use of **serverless architectures** in modernizing a microservices application to improve scalability, reduce operational overhead, and simplify workflows.

## 🏗 Architecture Overview
The Pet Store app is currently microservice-driven with messaging via RabbitMQ and a database backend. The proposal introduces **Azure Functions, Durable Functions, and Logic Apps** for event-driven and long-running workloads.

## 🔑 Topics Covered
1. **Overview of Algonquin Pet Store Architecture**  
   Understanding the baseline system.  
2. **Serverless Opportunities**  
   Identifying services that can be migrated to serverless functions.  
3. **Triggers & Bindings Design**  
   Leveraging Azure Functions Bindings for event-driven integration.  
4. **Function Chaining & Orchestration**  
   Using Durable Functions or AWS Step Functions for multi-step processes.  
5. **Handling Long-Running Processes**  
   Managing retries, timeouts, and compensation logic.  
6. **CI/CD & Deployment Pipelines**  
   Automating deployments with GitHub Actions or Azure DevOps.  
7. **Security, Monitoring & Observability**  
   Implementing Managed Identities, RBAC, and App Insights.  
8. **Logic Apps vs Azure Functions**  
   Evaluating low-code vs. code-first approaches for workflows.  
9. **Messaging & Event Routing**  
   Considering Azure Service Bus/Event Grid instead of RabbitMQ.  
10. **Serverless Best Practices & Summary**  
    Highlighting best practices and achieved improvements.

## ✅ Benefits
- **Pay-per-use model** reduces costs.  
- Automatic **scaling** for workloads without manual intervention.  
- Simplified orchestration of **multi-step workflows**.  
- Enhanced **observability** with centralized monitoring.  

## ⚠️ Challenges
- **Cold start latency** in serverless functions.  
- Migration complexity from RabbitMQ to cloud-native eventing.  
- Requires careful **cost monitoring** in event-driven architectures.  

## 📌 How to Use
1. Clone this repository.
2. Open the PowerPoint file with Microsoft PowerPoint or LibreOffice Impress.
3. Review slides and speaker notes for detailed explanations.
