Mysimplechat
This a quick chat app built for testing purpose. I've used Laravel 8 with 
Built with Laravel, Vue.js and Pusher. Follow the tutorial [https://pusher.com/tutorials/chat-laravel](https://pusher.com/tutorials/chat-laravel)

The master branch uses Pusher along with Laravel Echo.
The websocket branch uses laravel-websockets package instead. You have to keep php artisan websockets:serve command running in order to send/receive realtime messages.
Both work