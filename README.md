acessd
======
var remote = new RemoteControl();
remote.connect('http://localhost:81');
remote.on('next', function() {
    // Your method to move to the next slide
});

remote.on('previous', function() {
    // Your method to move to the previous slide
});
