# Arti Store

## Introduction
**Arti Store** is an online platform that allows art enthusiasts to discover and purchase unique, high-quality artwork. From classic paintings to contemporary digital art, Arti Store offers a diverse collection to suit every taste and style. This project showcases a full-stack e-commerce application, featuring user authentication, product management, and a seamless shopping experience.

- **Deployed Site:** [Arti Store Live](https://alitahaa.github.io/arti/)
- **Blog Article:** [Final Project Blog](#) (Insert the actual link)
- **Author's LinkedIn:** [Ali Taha](#)

## Screenshot
![Arti Store Screenshot](./Images/screenshot.png)  

## Installation
To run the project locally, follow these steps:

1. **Clone the repository**:
   ```bash
   git clone https://github.com/username/arti-store.git
   ```
2. **Navigate to the project directory**:
   ```bash
   cd arti-store
   ```
3. **Install dependencies**:
   - **Frontend**:
     - Open the `index.html` file in your browser.
   - **Backend**:
     - Navigate to the backend directory:
       ```bash
       cd backend
       ```
     - Create a virtual environment and activate it:
       ```bash
       python -m venv venv
       source venv/bin/activate  # On Windows use `venv\Scripts\activate`
       ```
     - Install the required packages:
       ```bash
       pip install -r requirements.txt
       ```
4. **Database Setup**:
   - Make sure MySQL is installed and running on your system.
   - Create a new database:
     ```sql
     CREATE DATABASE arti_store_db;
     ```
   - Update the database configuration in the `config.py` file.

5. **Run the application**:
   ```bash
   flask run
   ```

6. **Access the application**:
   - Open your browser and go to: `http://localhost:5000`

## Usage
- **Register** as a new user or **login** if you already have an account.
- Browse the **shop** to view the available products.
- Use the **filters** to narrow down products by category or price range.
- Add items to your **cart** and proceed to checkout.

## Contributing
Contributions are welcome! To contribute to this project, follow these steps:

1. **Fork the repository**.
2. **Create a new branch**:
   ```bash
   git checkout -b feature/YourFeatureName
   ```
3. **Commit your changes**:
   ```bash
   git commit -m "Add some feature"
   ```
4. **Push to the branch**:
   ```bash
   git push origin feature/YourFeatureName
   ```
5. **Create a Pull Request**.

## Related Projects
Here are some related projects that you might find interesting:
- [noon.com](https://www.noon.com/egypt-en/)
- [bluebookstores](https://bluebookstores.com/)

## License
This project is licensed under the MIT License.

---

### Resources
- [What your code repository says about you](https://opensource.com/open-organization/17/1/repo-tells-a-story)
- [Awesome List of READMEs](https://github.com/matiassingers/awesome-readme)
