# Ansible Udemy Course

Welcome to the Ansible Udemy Course repository! This repository contains all the code examples, playbooks, and exercises used throughout the course.

## 📚 Course Overview

This course is designed to teach you Ansible from the ground up, covering everything from basic concepts to advanced automation techniques. Whether you're a beginner or looking to enhance your existing skills, this course will provide you with practical, hands-on experience with Ansible.

## 🎯 Learning Objectives

By the end of this course, you will be able to:

- Understand Ansible architecture and core concepts
- Write and execute Ansible playbooks
- Manage inventory and host configurations
- Create and use Ansible roles for code reusability
- Work with variables, templates, and conditionals
- Handle loops and error management
- Deploy applications and manage infrastructure
- Implement best practices for Ansible automation

## 📋 Prerequisites

- Basic understanding of Linux/Unix systems
- Command line familiarity
- Basic networking concepts
- Text editor knowledge (vim, nano, or VS Code)

## 🛠️ Setup Instructions

### 1. Install Ansible

```bash
# On Ubuntu/Debian
sudo apt update
sudo apt install ansible

# On CentOS/RHEL
sudo yum install ansible

# Using pip
pip install ansible
```

### 2. Verify Installation

```bash
ansible --version
ansible-playbook --version
```

### 3. Clone This Repository

```bash
git clone https://github.com/FlorianPick/ansible_udemy.git
cd ansible_udemy
```

## 📁 Repository Structure

```
ansible_udemy/
├── README.md                 # This file
├── ansible.cfg              # Ansible configuration
├── inventory/               # Inventory files
│   ├── production
│   ├── staging
│   └── local
├── playbooks/               # Ansible playbooks
│   ├── basic/              # Basic examples
│   ├── intermediate/       # Intermediate examples
│   └── advanced/           # Advanced examples
├── roles/                  # Custom Ansible roles
├── group_vars/             # Group variables
├── host_vars/              # Host-specific variables
├── files/                  # Static files
├── templates/              # Jinja2 templates
└── requirements.yml        # Ansible dependencies
```

## 🚀 Getting Started

1. **Check your setup:**
   ```bash
   ansible localhost -m ping
   ```

2. **Run your first playbook:**
   ```bash
   ansible-playbook playbooks/basic/hello-world.yml
   ```

3. **Explore the examples:**
   - Start with files in `playbooks/basic/`
   - Progress through `playbooks/intermediate/`
   - Challenge yourself with `playbooks/advanced/`

## 📖 Course Modules

1. **Introduction to Ansible**
2. **Inventory Management**
3. **Ad-hoc Commands**
4. **Writing Your First Playbook**
5. **Variables and Facts**
6. **Conditionals and Loops**
7. **Handlers and Notifications**
8. **Templates with Jinja2**
9. **Ansible Roles**
10. **Error Handling**
11. **Ansible Vault**
12. **Advanced Playbook Techniques**
13. **Best Practices and Tips**

## 🤝 Contributing

If you find any issues or have suggestions for improvements, please feel free to:

1. Open an issue
2. Submit a pull request
3. Contact the instructor

## 📞 Support

If you need help with any of the course content:

- Check the course Q&A section
- Review the documentation in each module
- Refer to the [official Ansible documentation](https://docs.ansible.com/)

## 📄 License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

## 🎉 Happy Learning!

Remember: The best way to learn Ansible is by doing. Don't just read the code - run it, modify it, and experiment with it!

---

**Course Instructor:** Florian Pick  
**Course Platform:** Udemy  
**Last Updated:** 2025