# AWS S3 and Amazon QuickSight Project

## Table of Contents
- [Introduction](#introduction)
- [Project Overview](#project-overview)
- [Data Source](#data-source)
- [Resources](#resources)
- [Usage](#usage)
- [Conclusion](#conclusion)
- [License & Credits](#license-credits)
- [Contributors](#contributors)

## Introduction
This mini project demonstrates how to leverage AWS services, specifically Amazon S3 and Amazon QuickSight, to create data visualizations from large datasets. Amazon QuickSight is a powerful tool that enables the creation of interactive dashboards and reports, helping users gain valuable insights from their data.

## Project Overview
The main objective of this project is to:
1. Download a dataset of 50,000 best-selling Amazon products from GitHub.
2. Store the dataset in an Amazon S3 bucket.
3. Connect the S3 bucket to Amazon QuickSight and create engaging visualizations.

## Data Source
The dataset for this project is sourced from Bright Data, a leader in large-scale data collection, providing ready-to-use datasets for various applications. The dataset used here includes details of best-selling Amazon products.

## Resources
The following AWS resources were utilized to complete this project:
- **Amazon S3**: Used for storing the dataset.
- **Amazon QuickSight**: Used for data visualization and report creation.

## Usage
Follow these steps to replicate the project:

### Step 1: Clone the Repository
```bash
git clone https://github.com/DanieleBocchino/AWS-quicksight-project.git
```

### Step 2: Download Required Files
Download the following files from the GitHub page:
- `amazonbestseller.csv` (the dataset)
- `manifest.json` (configuration file)

### Step 3: Create an S3 Bucket
1. Log in to the AWS Management Console.
2. Navigate to **S3** and create a new bucket.

### Step 4: Upload the CSV File
Upload `amazonbestseller.csv` to the newly created S3 bucket.

### Step 5: Configure the `manifest.json` File
1. Open the `manifest.json` file.
2. Edit the configuration as necessary, following the setup instructions provided.

### Step 6: Connect S3 to Amazon QuickSight
1. Go to **Amazon QuickSight** in the AWS Management Console.
2. Configure a new data source that connects to your S3 bucket.
3. Create visualizations and reports using the dataset.

## Conclusion
This project serves as a practical guide to working with AWS services for creating visualizations. By following these steps, users can learn how to use Amazon S3 for data storage and Amazon QuickSight for interactive data analysis and reporting. Feel free to adapt the project for your specific use cases and explore different datasets to expand your data visualization skills.

## License & Credits
This project is open source and free to use. For any further information, please refer to the license included in this repository.

## Contributors
- **Janhvi Suchak** (Project Creator)

---
