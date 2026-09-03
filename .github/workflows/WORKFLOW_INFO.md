# GitHub Actions Workflows for Weather_data

This directory contains automated workflows to validate, test, and monitor your Weather_data project.

## 📋 Workflows Overview

### 1. **Notebook Validation** (`notebook-validation.yml`)
- **When:** On every push and pull request
- **What it does:**
  - Validates Jupyter notebook syntax
  - Checks notebook structure (cells, metadata)
  - Identifies notebook format issues
- **Duration:** ~1-2 minutes
- **Cost:** Free (public repo)

### 2. **Code Quality Checks** (`code-quality.yml`)
- **When:** On every push and pull request
- **What it does:**
  - Checks Python code formatting (Black)
  - Runs linting with flake8
  - Validates import organization (isort)
  - Reports style issues
- **Duration:** ~30 seconds
- **Cost:** Free (public repo)

### 3. **Actions Usage Metrics** (`usage-metrics.yml`)
- **When:** After notebook and code quality workflows complete, or weekly (Sunday)
- **What it does:**
  - Displays workflow execution summary
  - Logs workflow run timestamps
  - Provides link to GitHub Actions usage dashboard
- **Duration:** ~20 seconds
- **Cost:** Free (public repo)

## 🚀 How to Use

1. **View Workflow Status:**
   - Go to: https://github.com/tomMEM/Weather_data/actions
   - See all workflow runs in real-time

2. **Monitor Actions Usage:**
   - Go to: https://github.com/tomMEM/Weather_data/insights/actions/usage
   - View detailed metrics about workflow execution time and resources

3. **Check Individual Runs:**
   - Click any workflow run to see detailed logs
   - Expand steps to see what happened

## 📊 Understanding Actions Usage Metrics

The **Actions usage metrics** page shows:
- **Workflows:** How much time each workflow consumes
- **Jobs:** Which jobs are resource-intensive
- **Runners:** OS and runner type usage
- **Time Period:** Filter by week, month, year

### For Your Weather_data Project:
- Public repository = **unlimited free minutes**
- All workflows run for free
- No cost concerns

## 📝 Workflow Results

After each push:
1. Workflows automatically run
2. Results appear in the Actions tab (green ✓ or red ✗)
3. Notebooks are validated
4. Code quality issues are reported
5. Usage metrics are tracked

## 🔧 Customization

To modify workflows:
1. Edit `.github/workflows/*.yml` files
2. Commit and push changes
3. New workflows take effect immediately

## 📚 Learn More

- [GitHub Actions Documentation](https://docs.github.com/en/actions)
- [Actions Workflow Syntax](https://docs.github.com/en/actions/using-workflows/workflow-syntax-for-github-actions)
- [Actions Usage Metrics](https://docs.github.com/en/billing/managing-billing-for-github-actions/viewing-your-github-actions-usage)
