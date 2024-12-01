# Cloning the Repository

To clone this repository, follow these steps:

1. Open your terminal.
2. Navigate to the directory where you want to clone the repository.
3. Run the following command:

    ```sh
    git clone <repository-url>
    ```

4. Navigate into the cloned repository:

    ```sh
    cd <repository-name>
    ```

## Updating Configuration

### Update `baseurl` in `hugo.toml`

1. Open the `hugo.toml` file located in the root directory of the repository.
2. Find the `baseurl` parameter and update it with the appropriate URL.

    ```toml
    baseurl = "https://your-new-url.com/"
    ```

3. Save and close the file.

### Update CNAME URL in GitHub Actions Workflow

1. Open the `.github/workflows/something.yml` file.
2. Locate the section where the CNAME URL is specified.
3. Update the CNAME URL with the new URL.

    ```yaml
    - name: Update CNAME
      run: echo "your-new-url.com" > CNAME
    ```

4. Save and close the file.

You have now successfully cloned the repository and updated the necessary configuration files.