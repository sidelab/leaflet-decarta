var interleave = require('interleave');
    
task('build', function() {
    interleave('src', {
        path: 'dist',
        after: ['uglify']
    });
});

task('default', ['build']);
