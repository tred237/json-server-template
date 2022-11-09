# Mixology Buddy JSON Server

This JSON server is meant to be the back-end of the [Mixology Buddy](https://github.com/tred237/mixology-buddy) React app

## Setup

1. In Github, fork this repository.

![image](https://user-images.githubusercontent.com/103388556/189546584-8ec5fef7-4d7d-4c47-ae6b-f6e6ae834a69.png)

![image](https://user-images.githubusercontent.com/103388556/189546761-f0f05411-1967-46c7-b081-063bc6951ae0.png)

2. Copy the SSH key from the forked repository.

![image](https://user-images.githubusercontent.com/103388556/189546817-4d32dcbb-e79e-4220-8fc2-c573d21e9cc1.png)
  
3. In your terminal, clone the repository using the SSH key you copied from the fork.
```
git clone <pasted-ssh-key>
```
  
4. Navigate to the root of the cloned repository and install dependancie  
```
cd json-server-template
npm install
```

## Usage
1. In your terminal, navigate to the root of your back-end directory and copy data from the `db/seeds.json` file to the
`db/db.json` file.
```
cd json-server-template
npm run seed
```

Note: You can run `npm run seed` if you ever want to overwrite `db.json` to reflect the default seed.

2. Launch your JSON server in development mode. The output should confirm that the server has started and will provide you with the localhost URL and port that the sever is running on.
 ```
 npm run dev
 ```

<img width="337" alt="image" src="https://user-images.githubusercontent.com/103388556/200965932-85812984-3c84-4534-b01e-c34474cbf05a.png">

3. Once you know your JSON server is running, you are able to start your front-end. You can find the Usage instructions for this [here](https://github.com/tred237/mixology-buddy).

## License/API

All of the data was pulled from the [TheCocktailDB API](https://www.thecocktaildb.com/api.php?ref=apilist.fun)
