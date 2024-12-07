# Sample Javascript/ReactNative

Thoughts is a mobile application built using react native that allows user to share their thoughts with others.

## 🚀 Getting Started  

### Open Using Daytona  

1. **Install Daytona**: Follow the [Daytona installation guide](https://www.daytona.io/docs/installation/installation/).  

2. **Create the Workspace**:  
   ```bash  
   daytona create https://github.com/parikshitadhikari/thoughts-reactnative-daytona.git 
   ```  

3. **Start the Application**:  
In order to start this project, firstly you'll need to setup `expo` in your Mobile or need and an Android or iOS simulator.

After, expo setup, following steps shall be performed

1. Execute `npm start` to run the client side.

2. Navigate to the `backend` directory and create a `.env` file and add the following:
```
NODE_ENV=development
MONGO_URI=*********** 
JWT_SECRET=*******
```
Now, run `npm start` to start the server.

## ✨ Features  
- Authentication
- Update user profile
- Add, Delete and Edit Thoughts
- Search thoughts