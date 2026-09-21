const audiocontainer = document.querySelector('.audio')
const audio = document.querySelector('.mp3')
 audiocontainer.addEventListener('mouseenter', () => {
    audio.play();
 });
 audiocontainer.addEventListener('mouseleave', () => {
    audio.pause();
    audio.currentTime = 0;
 });