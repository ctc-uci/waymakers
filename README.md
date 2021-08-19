
# Waymakers
![Waymakers Logo](https://media-exp1.licdn.com/dms/image/C4E1BAQFYOCQ-2SCftw/company-background_10000/0/1521837604390?e=2159024400&v=beta&t=1JHqCVw9FztoFSgZ8YC2AHKpCjSl4z_yCOTyqSuAFn0)
#### Waymakers seeks to build safer communities by helping individuals make their way through conflict and crisis to a place of strength and stability.

**🌐** [Website](https://waymakersoc.org) | [Twitter](https://twitter.com/WaymakersOC) | [Facebook](https://www.facebook.com/WaymakersOC/) | [Instagram](https://www.instagram.com/WaymakersOC)


![Waymakers Website Preview](https://i.imgur.com/BNwFMsO.png)


## 🔎 About the Project

*Most of Waymakers' internal processes were kept through paper and repeatedly printed, copied, and distributed. This wasted away thousands of hours each year which could have been better spent helping individuals through conflict.*


🆙 We built an online system for Waymakers to track their internal inventory, store and look up volunteer information, and create events for volunteers to participate in and log their hours. This solution helped Waymakers administrators to more easily facilitate volunteer organization and inventory management while reducing costs of paperwork and physical storage.


**Tech Stack:**

Frontend - React
Backend - NodeJS + PostgreSQL

## 💻 Development 

### 🔨 Getting Set Up

1. **Clone the project.**
	
	The --recursive flag will download both the frontend and backend submodule repos.
	
	`git clone --recursive git@github.com:ctc-uci/waymakers.git`

2. **Install the dependencies.**

	A postinstall script will also run to install dependencies in the submodules.

	`npm install`
	
3. **Add the `.env` files to `waymakers-frontend` and `waymakers-backend`.**

### 💨 Running the Project

- `npm start` will run the frontend and backend concurrently
- To start the frontend or backend separately, `cd` into its respective directory and use `npm start` there.