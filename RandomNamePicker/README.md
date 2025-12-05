
# Random Selector - Carrom King Theme

A visually appealing, animated random selector wheel with a Carrom King theme. Perfect for games, contests, or any situation where you need to randomly select a winner with style.

## Features

- 🎡 Animated spinning wheel with smooth animations
- 🎨 Beautiful Carrom King themed UI with vibrant colors
- 🎉 Celebration effects with confetti and congratulations overlay
- ⚙️ Customizable participant list with ID:name format
- 🔗 Shareable URLs with encoded participant lists
- 📱 Responsive design that works on mobile and desktop
- 🎯 Accurate random selection algorithm
- 🔊 Haptic feedback support (on compatible devices)


  ### Sharing Participant Lists

The application automatically encodes your participant list in the URL, making it easy to share. Just copy the URL from your browser after setting up your participants.

### URL Parameters

- `list`: Encoded participant list (automatically managed by the application)


## Technical Details

### Dependencies

- [Tailwind CSS](https://tailwindcss.com/) - For styling
- [GSAP](https://greensock.com/gsap/) - For animations



### Animation Settings

You can adjust animation parameters in the JavaScript section:
- `REPEAT`: Number of times to duplicate items for seamless looping
- Spin duration and easing functions in the `spinToSelect` function
- Confetti quantity and colors in the `spawnConfetti` function


## Acknowledgments

- Carrom King for the theme inspiration
- Greensock for the powerful GSAP animation library
- Tailwind CSS for the utility-first CSS framework
