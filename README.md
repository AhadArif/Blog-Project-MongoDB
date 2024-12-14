## 🚀 **Getting Started**

Follow the steps below to set up and run the project locally.

---

### **1. Prerequisites**
Ensure you have the following installed on your machine:
- [Node.js](https://nodejs.org/) (LTS version recommended)
- [MongoDB Atlas](https://www.mongodb.com/) (Free Cluster Setup)

---

### **2. Database Setup**
1. **Sign Up for MongoDB**  
   - Visit [MongoDB Atlas](https://www.mongodb.com/) and create a free account.
   - Set up a **free database cluster**.
   - Obtain your MongoDB connection URI (you'll use this in the next step).

2. **Create `.env` File**  
   - In the root directory of the project, create a `.env` file.
   - Add your database URI and secret key as shown below:

     ```env
     MONGODB_URI=mongodb+srv://<username>:<password>@clusterName.xxxxxxx.mongodb.net/<database>
     JWT_SECRET=MySecretBlog
     ```

   Replace `<username>`, `<password>`, `<clusterName>`, and `<database>` with your actual MongoDB credentials and database name.

---

### **3. Installation**
1. Clone the repository:
   ```bash
   git clone https://github.com/your-username/your-repository.git
   cd your-repository

2. Install dependencies:

 npm install

3. Start the development server:

 npm run dev


4. Contributing
Feel free to submit issues or pull requests for improvements! Contributions are welcome.

5. License
This project is licensed under the MIT License.

This project was inspired by RaddyTheBrand. I used references and guidance from their work and made modifications to suit my project’s needs.
