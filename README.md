<div align="center">

  
  <div align="center">
    <h3>🎬 Сцена загрузки системы...</h3>
    <div style="font-family: 'Cascadia Code', monospace; font-size: 1.2rem; color: #00FFFF; text-align: left; max-width: 600px; margin: 40px auto; padding: 20px; background: rgba(0, 0, 0, 0.3); border-radius: 10px; border-left: 4px solid #00FFFF;">
      <pre style="margin: 0; color: #00FFFF;">
Инициализация системы... <span style="color: #3DDC84;">OK</span>
Загрузка профиля разработчика...
Имя: <span style="color: #FF6B8B;">Руслан Кулиев</span>
Специализация: <span style="color: #7F52FF;">Android Developer</span>
Уровень: <span style="color: #00FFFF;">Junior → Middle</span>
Локация: <span style="color: #26A5E4;">Москва, Россия</span>
Образование: <span style="color: #3DDC84;">МФЮА | Computer Science</span>
Загрузка завершена <span style="color: #3DDC84;">✅</span>
<span style="color: #00FFFF; font-weight: bold;">Добро пожаловать в мой мир кода 🚀</span>
      </pre>
      <span style="animation: blink 1s infinite; font-weight: bold; color: #00FFFF;">|</span>
    </div>
  </div>

  
  <br>
  <img src="https://readme-typing-svg.demolab.com?font=Fira+Code&weight=600&size=32&duration=3000&pause=1000&color=00FFFF&width=500&lines=fun+main()+{+println('Hi!')+};Ruslan+Kuliyev;Kotlin+Developer;t.me/moyakov1" alt="Typing Animation" />

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
