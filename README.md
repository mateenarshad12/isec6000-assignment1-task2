**Task2: Microservices Architecture and Deployment**
1. **First requirement docker should be installed in your ubuntu.**
2. **Fork saleor platform repository.** using from the following [link](https://github.com/saleor/saleor-platform)
3. **clone the directory in ubuntu** using command. git clone https://github.com/saleor/saleor-platform.git
4. **Go to the cloned directory** using command . $ cd saleor-platform
5. **Build the applications** using command. $ docker compose build
6. **Apply Django migrations** using command. $ docker compose run --rm api python3 manage.py migrate
7.  
![1](https://github.com/mateenarshad12/saleor-platform/assets/143591402/ed9a48a9-d7a7-4fc6-aa4c-6f2c160ca5b2)
8. 
![2](https://github.com/mateenarshad12/saleor-platform/assets/143591402/08a8da92-fac0-4ce9-bb04-877fe67008ce)

9. **Assign a saleor Dashboard port 9000 to 9003.** or this make a change of port in compose.yml file.
10. **Down the docker** using following command. $ docker compose down
11. **Start docker** using following command.$ docker compose up
![1](https://github.com/mateenarshad12/isec6000-assignment1-task2/assets/143591402/60d7b8b9-9b52-4824-a8d8-688e98b46515)



**Full Changelog**: https://github.com/mateenarshad12/saleor-platform/commits/isec6000-assignment1
