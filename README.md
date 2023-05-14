
# Introduction
## Videoshare

- Youtube Video Sharing App

- Using Ruby/Rails or a related Ruby framework. The application should include a real-time notification system to showcase the backend development skills.

## Key Features

- User registration and login

- Sharing YouTube videos

- Viewing a list of shared videos (no need to display up/down votes)

- Real-time notifications for new video shares: When a user shares a new video, other logged-in users should receive a real-time notification about the newly shared video. This notification can be displayed as a pop-up or a banner in the application, and it should contain the video title and the name of the user who shared it.

# Prerequisites

# Installation & Configuration & Database

- rename `.env_example` to `.env` and input some config

### Local Setup

- install Ruby 3.1.1 & rails 7.0.4
- install posgresql
- install redis
- run `bundle install` then run `rails s`

### Docker

- install docker
- run

```
  docker compose build
  docker-compose run web rake db:reset
  docker-compose run web rake db:create
  docker-compose run web rake db:migrate
  docker-compose up -d
```

rails db:create



# Running the Application

# Deployment

# Usage

# Troubleshooting

# Steps 

```
rails new . -d postgresql -j esbuild -c tailwind -T
```