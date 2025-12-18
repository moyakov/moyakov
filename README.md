<div align="center">

    <h3>🎬 Сцена загрузки системы...</h3>
    
    <div style="font-family: 'Cascadia Code', monospace; font-size: 1.2rem; color: #00FFFF; text-align: center; max-width: 600px; margin: 40px auto; padding: 20px; background: rgba(0, 0, 0, 0.3); border-radius: 10px; border-left: 4px solid #00FFFF;">
    
    <div id="final-text" style="display: block;">
        <div style="color: #FF6B8B; font-size: 1.5rem; font-weight: bold;">Руслан Кулиев</div>
        <div style="color: #7F52FF; font-size: 1.2rem;">Android Developer</div>
        <div style="color: #00FFFF; margin-top: 10px; font-size: 1rem;">
            Москва, Россия | МФЮА | Junior → Middle
        </div>
    </div>
    
    <div style="color: #3DDC84; margin-top: 20px; font-size: 0.9rem;">
        <span class="dot1">●</span>
        <span class="dot2">●</span>
        <span class="dot3">●</span>
    </div>
    
    </div>
</div>

<style>
    .dot1, .dot2, .dot3 {
        opacity: 0;
        animation: dotAnimation 1.5s infinite;
    }
    
    .dot2 { animation-delay: 0.5s; }
    .dot3 { animation-delay: 1s; }
    
    @keyframes dotAnimation {
        0%, 100% { opacity: 0; }
        50% { opacity: 1; }
    }
    
    @keyframes blink {
        0%, 50% { opacity: 1; }
        51%, 100% { opacity: 0; }
    }
</style>

  
  <br>
  <img src="https://readme-typing-svg.demolab.com?font=Fira+Code&weight=600&size=32&duration=3000&pause=1000&color=00FFFF&width=500&lines=val+name+%3D+'Ruslan';val+role+%3D+'Android+Dev';Kotlin+%7C+Jetpack+Compose;Connect+on+Telegram" alt="Typing Animation" />

  <p align="center">
    <img src="https://img.shields.io/badge/Status-Coding%20the%20Future-00FFFF?style=for-the-badge&logo=visual-studio-code&logoColor=white&labelColor=0d1117&borderColor=0077FF" alt="Status" />
    <img src="https://img.shields.io/badge/Mode-Creative%20Flow-7F52FF?style=for-the-badge&logo=creative-commons&logoColor=white&labelColor=0d1117&borderColor=7F52FF" alt="Mode" />
  </p>

  <img src="https://raw.githubusercontent.com/andreasbm/readme/master/assets/lines/rainbow.png" alt="Rainbow divider" width="100%" height="2" />
</div>

## 🛰️ **Системный профиль**
<p align="justify">
  <img src="https://img.shields.io/badge/Уровень-Junior%20Developer-7F52FF?style=flat-square&logo=rocket&logoColor=white&labelColor=0d1117" alt="Level" />
  <img src="https://img.shields.io/badge/Направление-Android%20Development-3DDC84?style=flat-square&logo=android&logoColor=white&labelColor=0d1117" alt="Focus" />
</p>

```kotlin
data class DeveloperProfile(
    val name: String = "Ruslan Kovalev",
    val role: String = "Android Developer",
    val level: String = "Junior → Middle",
    val location: String = "Moscow, RU",
    val education: String = "MFUA | Computer Science",
    val status: Status = Status.CODING,
    val passion: String = "Creating mobile magic ✨"
)

enum class Status {
    CODING, LEARNING, INNOVATING, DEBUGGING
}

val myProfile = DeveloperProfile().apply {
    println("🚀 Профиль загружен: $name")
    println("💼 Специализация: $role")
    println("📚 Текущий статус: ${status.name}")
}
