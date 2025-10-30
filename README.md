# Wavesurfer JS and Astro simple visualizer

A simple audio visualizer component for the Astro framework created with Wavesurfer JS. It is minimal and ready to use right away. You can copy and paste it into your own projects just like I do. There might be better ways to build it but this one works well. Enjoy!

## Usage

```astro
    ---
    import WaveformPlayer from '../components/AudioPlayer.astro';
    ---
    <!-- Your content here -->
    <WaveformPlayer audioSrc="/src/file.mp3" progressColor="#33fa12" />
```