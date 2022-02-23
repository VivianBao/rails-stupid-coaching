# README

# 📖 Stupid Coaching

A practice project using Ruby On Rails, in which a grumpy, but simple minded coach who cares about you trying its best to motivate you to go to work!

<!-- _DROP SCREENSHOT HERE_
<br>
App home: https://WHATEVER.herokuapp.com -->


## Getting Started
### Setup

Install gems
```
bundle install
```
Install JS packages
```
yarn install
```

### ENV Variables
Create `.env` file
```
touch .env
```
Inside `.env`, set these variables. For any APIs, see group Slack channel.
```
CLOUDINARY_URL=your_own_cloudinary_url_key
```

### DB Setup
```
rails db:create
rails db:migrate
rails db:seed
```

### Run a server
```
rails s
```

## Built With
- [Rails 6](https://guides.rubyonrails.org/) - Backend / Front-end
- [Heroku](https://heroku.com/) - Deployment
- [PostgreSQL](https://www.postgresql.org/) - Database


## Acknowledgements
One of the challenges of Le Wagon Tokyo Full Stack Developer couse.

## Team Members
- [Vivian Bow](https://github.com/VivianBao/)

## Contributing
Pull requests are welcome. For major changes, please open an issue first to discuss what you would like to change.

## License
This project is licensed under the MIT License
