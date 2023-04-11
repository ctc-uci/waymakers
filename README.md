
# Waymakers
![Waymakers Logo](https://user-images.githubusercontent.com/45449494/130122579-62bf330a-8133-40df-bb67-fe27115de1c9.jpg)
#### Waymakers seeks to build safer communities by helping individuals make their way through conflict and crisis to a place of strength and stability.

**🌐** [Website](https://waymakersoc.org) | [Twitter](https://twitter.com/WaymakersOC) | [Facebook](https://www.facebook.com/WaymakersOC/) | [Instagram](https://www.instagram.com/WaymakersOC)


![WMK Web Preview](https://user-images.githubusercontent.com/45449494/130122650-c59c3aa8-7958-489e-a8e3-ea539dd514b6.png)


## 🔎 About the Project

*Most of Waymakers' internal processes were kept through paper and repeatedly printed, copied, and distributed. This wasted away thousands of hours each year which could have been better spent helping individuals through conflict.*


🆙 We built an online system for Waymakers to track their internal inventory, store and look up volunteer information, and create events for volunteers to participate in and log their hours. This solution helped Waymakers administrators to more easily facilitate volunteer organization and inventory management while reducing costs of paperwork and physical storage.

![Events](https://user-images.githubusercontent.com/45449494/130122712-6ad5f2d8-56a4-4fb6-832c-c062c2f4e377.png)
![User Directory](https://user-images.githubusercontent.com/45449494/130122763-2361c4cd-6cc3-4d8d-bd36-f0f3cd5b70de.png)
![Inventory](https://user-images.githubusercontent.com/45449494/130122788-f2f8ef63-cb62-4f8b-b438-95f3eed74e09.png)
![Sign-in](https://user-images.githubusercontent.com/45449494/130122813-97c208ad-9c57-4d42-ae10-009193f7d011.png)


**Tech Stack:**

**🔼 Frontend:** React

**🔽 Backend:** NodeJS + PostgreSQL


## 💻 Development 

### 🔨 Getting Set Up

1. **Clone the project.**
	
	The `--recursive` flag will download both the frontend and backend submodule repos.
	
	`git clone --recursive https://github.com/ctc-uci/waymakers`

2. **Install the dependencies.**

	A postinstall script will also run to install dependencies in the submodules.

	`yarn install`
	
3. **Add `.env`s and other secret files to `waymakers-frontend` and `waymakers-backend`.**


### 💨 Running the Project

- `yarn start` will run the frontend and backend concurrently
- To start the frontend or backend separately, `cd` into its respective directory and use `yarn start` there.
- To update sub-repositories, use `git submodule update --remote` at the base or `cd` into a subdirectory and do `git pull`.