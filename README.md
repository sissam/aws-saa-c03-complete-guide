# aws-saa-c03-complete-guide
aws-saa-c03-complete-guide

'''
graph TD
    subgraph "EC2 Instances"
        A[On-Demand]
        B[Reserved Instances]
        C[Spot Instances]
    end
    subgraph "Serverless"
        D[AWS Lambda]
    end
    subgraph "Containers"
        E[Amazon ECS]
        F[Amazon EKS]
    end
    subgraph "Optimization Tools"
        G[AWS Compute Optimizer]
        H[Auto Scaling Groups]
    end

    A -- "Short-term, Irregular" --> A
    B -- "Predictable Usage, Discount" --> B
    C -- "Fault-tolerant, Flexible, Deep Discount" --> C
    D -- "Event-driven, No Servers" --> D
    E -- "Managed Docker" --> E
    F -- "Managed Kubernetes" --> F
    G -- "Right-sizing Recommendations" --> A
    H -- "Elastic Workloads" --> A
'''
