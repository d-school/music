## playSound()

```
    func playSound() {
        let url = Bundle.main.url(forResource: "ド", withExtension: "mp3")
        player = try! AVAudioPlayer(contentsOf: url!)
        player.play()
                
    }
```
