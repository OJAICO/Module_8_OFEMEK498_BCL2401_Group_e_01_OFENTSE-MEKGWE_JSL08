
# Bank Branch Singleton Pattern

Welcome to my Bank Branch Singleton Pattern project! In this project, I've implemented the Singleton Pattern to manage bank branch information effectively.

## Overview

This project demonstrates the Singleton Pattern by creating a single instance of the `BankBranch` class. The Singleton Pattern ensures that throughout the application, there's only one set of branch information, even if multiple instances of the `BankBranch` class are created.

## Implementation

1. **Singleton Instance**: The `bankBranchInstance` variable is used to store the singleton instance of the `BankBranch` class.

2. **BankBranch Class**: The `BankBranch` class is defined to manage branch information. It includes a constructor that checks if the `bankBranchInstance` variable is null. If it's null, a new instance is created with the provided branch information; otherwise, it returns the existing instance.

3. **Branch Management Methods**: Additional methods, like `getBranchInfo`, are included in the `BankBranch` class to manage branch-related information.

4. **Usage**: Instances of the `BankBranch` class, such as `branchA` and `branchB`, are created with different branch information. The `getBranchInfo` method is used to retrieve branch information from these instances. Finally, it's verified that both `branchA` and `branchB` point to the same instance.

## Usage

1. **Create Instances**: Instantiate the `BankBranch` class to create instances representing different bank branches, providing branch information as parameters.

2. **Retrieve Branch Info**: Use the `getBranchInfo` method to retrieve branch information from the instances.

3. **Verify Singleton**: Verify that multiple instances of the `BankBranch` class point to the same singleton instance by comparing them using `===`.

## About Me

Hi, I'm Ofentse Mekgwe, a software developing student with a passion for learning about design patterns and software architecture. This project is one of my early attempts at implementing design patterns, and I'm excited to share it with you!

Feel free to explore the code and reach out if you have any questions or suggestions. Let's learn and grow together in the world of software development!
