# HSPlayer
This is a simple video player built using AVFoundation with a deoplyment target of 4.0
Built just for fun and as a good reference of a clean player implementation.

Interface:
 ```objective-c
@property (nonatomic, strong, readonly) AVPlayer *player;

// Start player by setting the URL
@property (nonatomic, copy) NSURL *URL;

@property (nonatomic, assign) BOOL playing;

@property (nonatomic, assign) BOOL controlsVisible;
- (void)setControlsVisible:(BOOL)controlsVisible animated:(BOOL)animated;

// Hides statusBar if true, defaults to YES
@property (nonatomic, assign) BOOL fullScreen;
 ```

## License
HSPlayer is released under the MIT-license (see the LICENSE file)
