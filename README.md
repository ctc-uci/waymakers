
# Waymakers
![Waymakers Logo](https://media-exp1.licdn.com/dms/image/C4E1BAQFYOCQ-2SCftw/company-background_10000/0/1521837604390?e=2159024400&v=beta&t=1JHqCVw9FztoFSgZ8YC2AHKpCjSl4z_yCOTyqSuAFn0)
#### Waymakers seeks to build safer communities by helping individuals make their way through conflict and crisis to a place of strength and stability.

**🌐** [Website](https://waymakersoc.org) | [Twitter](https://twitter.com/WaymakersOC) | [Facebook](https://www.facebook.com/WaymakersOC/) | [Instagram](https://www.instagram.com/WaymakersOC)


![Waymakers Website Preview](https://i.imgur.com/BNwFMsO.png)


## 🔎 About the Project

*Most of Waymakers' internal processes were kept through paper and repeatedly printed, copied, and distributed. This wasted away thousands of hours each year which could have been better spent helping individuals through conflict.*


🆙 We built an online system for Waymakers to track their internal inventory, store and look up volunteer information, and create events for volunteers to participate in and log their hours. This solution helped Waymakers administrators to more easily facilitate volunteer organization and inventory management while reducing costs of paperwork and physical storage.

![Events](https://lh3.googleusercontent.com/GCa_eprzkizmtgWzGC0aOKYkf2d2vQgmEXXKvRORKu8bSnAbiVZUsK5sM3O2C59Khxihl5ByrEZ-cKjkEE1Z=w1343-h1283)
![User Directory](https://lh3.googleusercontent.com/wnztl915lHbvABXD-qOzQL031CUdAYm_gJQFxFsN2tJO_t77AaFvXFq5nsDVrDX3J93nJnCD4EYxqFL0DbKU=w1343-h1283)
![Inventory](https://lh6.googleusercontent.com/hiyPIwBGmRFAPn6lU0gDKF5RvcdGTkRRqLul4TfyCX2WZFBxXQtw6wdSicGeOoBSq2z5es7gDLwi5sXkwWCT=w1343-h1283)
![Sign-in](https://lh3.googleusercontent.com/_G8LH1cULT0xXf93f-fiJlv-tx9cNeE04pExFxPiAN9aaXOkGewZ8nDfXCLFFi5dx3ItxcDIM1F0ooT22L8a=w1343-h1283)

**Tech Stack:**

**Frontend:** React

**Backend:** NodeJS + PostgreSQL


## 💻 Development 

### 🔨 Getting Set Up

1. **Clone the project.**
	
	The `--recursive` flag will download both the frontend and backend submodule repos.
	
	`git clone --recursive git@github.com:ctc-uci/waymakers.git`

2. **Install the dependencies.**

	A postinstall script will also run to install dependencies in the submodules.

	`npm install`
	
3. **Add the `.env` files to `waymakers-frontend` and `waymakers-backend`.**


### 💨 Running the Project

- `npm start` will run the frontend and backend concurrently
- To start the frontend or backend separately, `cd` into its respective directory and use `npm start` there.