# Counter (Github Actions Study)

This repository contains automated workflows that increment counters daily, weekly, monthly, and yearly using GitHub Actions. Each counter is stored in a separate file and is updated automatically based on the specified schedule.

## Files and Structure

- **counter_daily.txt** – Stores the daily counter, incremented every day.
- **counter_weekly.txt** – Stores the weekly counter, incremented every Sunday.
- **counter_monthly.txt** – Stores the monthly counter, incremented on the first day of each month.
- **counter_yearly.txt** – Stores the yearly counter, incremented on January 1st of each year.

## GitHub Actions Workflows

The following GitHub Actions workflows handle automated increments:

1. **Daily Counter Increment**:

   - Triggered daily at midnight UTC.
   - Located in `.github/workflows/daily_increment.yml`.

2. **Weekly Counter Increment**:

   - Triggered every Sunday at midnight UTC.
   - Located in `.github/workflows/weekly_increment.yml`.

3. **Monthly Counter Increment**:

   - Triggered on the first day of each month at midnight UTC.
   - Located in `.github/workflows/monthly_increment.yml`.

4. **Yearly Counter Increment**:

   - Triggered on January 1st at midnight UTC.
   - Located in `.github/workflows/yearly_increment.yml`.

## How It Works

Each workflow:

1. **Pulls** the latest changes from the main branch.
2. **Reads** the current count from the respective counter file.
3. **Increments** the count by 1.
4. **Commits and pushes** the updated file back to the repository.

## Running the Workflows Manually

In addition to their scheduled runs, each workflow can be triggered manually via the "Actions" tab on GitHub. This is useful for testing or for manually updating counters.

## Setup

To create a similar setup:

1. Clone this repository by running:
   ```bash
   git clone https://github.com/davesheinbein/Counter.git
   ```
2. Ensure the GitHub Actions workflows are located in `.github/workflows/`.
3. Confirm that each `.yml` file has a `GITHUB_TOKEN` available for authentication in the repository settings.

## Contact

#### 📫 How to reach me:

###### [(310)-628-5770](tel:310-628-5770) | [Davidsheinbeindev@gmail.com](mailto:davidsheinbeindev@gmail.com) | [LinkedIn](https://www.linkedin.com/in/david-sheinbein/)

###### [Schedule A Meeting](https://calendly.com/davidsheinbeindev/intro)

For any questions, please contact [Davidsheinbeindev@gmail.com](mailto:Davidsheinbeindev@gmail.com).
