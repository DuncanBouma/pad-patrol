# 🕵🏠 Pad Patrol

## Find your next place faster

Pad Patrol is a small tool that watches a list of supplied URLs for changes. When it sees a change, it will send an SMS to your phone with the changed URL, meaning you won't need to endlessly refresh pages ever again 😎

**Note** _Pad Patrol is in a serious infancy, and currently only works with [Kijiji](http://www.kijiji.com) links. Feel free to make any contributions if you end up adapting it for other sites 🚀_

### Usage

To get started, you'll need to sign up for a [twilio account](https://www.twilio.com/try-twilio) (They offer a free trial that should accomodate the duration of your apartment hunt).

Once that's done, you'll need clone this repo

```bash
$ git clone https://github.com/quinnlangille/pad-patrol.git
```

Because most of the info involved with Twilio is user confidential, we use [.dotenv](https://github.com/motdotla/dotenv) to keep private info safe. To use it you'll add some envionmental variables to the `.env` file in the root of this project


Finally, once your ENV's have been added, finish with the usual

```bash
$ yarn install // or npm install
$ yarn start
```

That's it - Happy hunting 🕵!
