# Problem 3: Unsupervised Learning - Automated Exam Management System 🎓📊

## Problem Statement

You are required to design and implement an automated exam management system that can efficiently manage the seating plan and faculty allocation for students in various domains. The system should use the **K-means clustering** technique to automate the seating plan and faculty allocation. The system must group students from the following batches and domains:

- **Batches**: 19, 20, 21, 22
- **Domains**: Computer Science, Artificial Intelligence, Business Analytics, Software Engineering, Electrical Engineering

The project will help in automating the seating plan creation and faculty duty allocation by efficiently utilizing room capacities, batch distribution, and domain-based groupings.

### Problem Overview:

- **Rooms**: 30 rooms available, each with varying seat capacities (25-35 students).
- **Students**: 2400-2500 students across multiple domains and batches.
- **Faculty**: Faculty members available for each domain.

### Key Tasks:

1. **Data Collection**: 
   - Collect data about the number of students in batches 19, 20, 21, 22 across the domains.
   - Collect information about the room capacities (with varying seat capacities).
   
2. **Data Preprocessing**: 
   - Clean and preprocess the collected data to make it suitable for K-means clustering.

3. **K-Means Clustering**: 
   - Use K-means to cluster students based on their domains and batch numbers.
   - Determine the optimal number of clusters based on domain and batch distribution.

4. **Seating Plan**: 
   - Generate a seating plan for each room based on the clusters formed.
   - Ensure the room capacity is not exceeded and optimize seating arrangements for minimal disruptions.

5. **Faculty Allocation**: 
   - Allocate faculty members to each room based on the clusters and their expertise in corresponding domains.

6. **Reporting**: 
   - Generate a report summarizing the seating plan and faculty allocation for each exam.

## Project Goals 🎯:

1. Use **K-means clustering** to group students by domains, ensuring that students from the same domain sit together.
2. Ensure that room capacities are utilized efficiently without exceeding limits, considering batch distributions.
3. Assign faculty members to each exam room based on their domain expertise.

## Project Deliverables 📦:

1. **K-means Clustering Algorithm**: 
   - Group students based on domains of study using K-means.
   
2. **Seating Plan Generation**: 
   - An algorithm to generate an optimized seating plan.
   
3. **Faculty Allocation**: 
   - An algorithm to assign faculty members based on their expertise.

4. **User Interface**: 
   - A user-friendly interface for administrators to input student/faculty data and view the generated seating plan and faculty assignments.

## Evaluation Criteria ✅:

- Correct implementation and functionality of **K-means clustering**.
- **Accuracy** and efficiency of the seating plan generation considering batch distribution and room capacities.
- **Correctness** of faculty assignments based on domain expertise.
- **Code Quality**: Scalability, maintainability, and clarity.

## Implementation Guidelines ⚙️:

- **Programming Language**: Python
- **Libraries**: NumPy, Pandas, Scikit-learn
- **Modular Code**: Design the code for scalability and ease of maintenance.
- **Documentation**: Document each step of the implementation process.
- **Testing**: Test the system with both sample datasets and real-world scenarios for accuracy.

---

By completing this project, you will automate the process of seating students and assigning faculty to exam rooms using clustering techniques, improving both efficiency and accuracy.
