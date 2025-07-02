# 🔐 What is IAM (Identity and Access Management)?

IAM is a **security service** in AWS used to manage **who can access what** in your AWS account.

It helps you control **access to AWS services and resources** securely.

---

## 🧠 Key Concepts

### 👤 IAM User
- Represents a single person or app
- Gets long-term credentials (username, password, access keys)

### 👥 IAM Group
- A collection of IAM users
- Attach policies to groups to assign permissions to many users at once

### 🎭 IAM Role
- Temporary identity with specific permissions
- Used by services (like EC2) or external users (like third-party apps)
- No long-term credentials

### 🛡️ IAM Policy
- JSON document that defines permissions (Allow/Deny)
- Attached to users, groups, or roles

---

## 🔑 Why IAM is Important

- Controls **who can do what**
- Helps follow **least privilege** principle
- Prevents **unauthorized access**

---

## 🧪 Real-Life Analogy

- IAM User → Employee with an ID card  
- IAM Role → Visitor badge with limited access  
- IAM Policy → Rules on where they can go  
- IAM Group → Department with same access level

---

## 🧰 Example Use Case

- You create a user for a developer 👨‍💻  
- You give them S3 read/write access only  
- You use IAM policy to define exactly what they can access
- then remove th access after work done

---

