<h1 align="center">Hi, I'm dreule 👋</h1>
<p align="center">
  🧠 From medicine to memory-safe systems<br>
  🎓 Peer at 42 Heilbronn · Creative C hacker · Parser enjoyer
</p>

---

## 🔧 Currently Building

I'm exploring the low-level world through the 42 core curriculum — writing everything from scratch using C, Unix syscalls, and raw memory management. Here's what I've been up to:

---

### 🐚 [minishell](https://github.com/dreule/minishell)
A custom UNIX shell built from scratch — includes pipes, redirections, signals, environment expansion, and more.

> 👤 Parsing: [@dreule](https://github.com/dreule)  
> ⚙️ Execution: [@gzovkic](https://github.com/gzovkic)

#### 🔄 Parsing Logic (my part)
- Tokenization with quote-aware splitting
- Syntax tree for pipes & redirections
- Variable expansion with `$VAR`, `$?`
- Bash-compliant error handling for malformed input

#### ⚙️ Execution Engine (by @gzovkic)
- Builtin and external command execution
- Pipeline construction with `pipe()` and `dup2()`
- Redirection logic and heredoc handling
- Process lifecycle, signals, and exit code tracking

---

### 🌌 [fract'ol](https://github.com/dreule/fract-ol)
An interactive fractal explorer using MiniLibX.  
Supports zooming, mouse-driven navigation, and color-shifting effects.

> Features Mandelbrot, Julia, Burning Ship, and more.

🎨 Bonus features:
- Smooth zoom around mouse
- Arrow-key panning
- Dynamic palette cycling

<p align="center">
  <a href="https://github.com/dreule/fract-ol/blob/main/screenshots/julia.png" target="_blank">
    <img src="https://img.shields.io/badge/View-Julia_Screenshot-blue?style=for-the-badge" alt="Julia Screenshot"/>
  </a>
</p>

---

## 🛠️ Core Projects

| Project        | Description                                          | Link                                  |
|----------------|------------------------------------------------------|---------------------------------------|
| `ft_printf`    | Custom `printf()` implementation                     | [Repo](https://github.com/dreule/ft_printf) |
| `get_next_line`| Line-by-line file reader using static buffers        | [Repo](https://github.com/dreule/get_next_line) |
| `minitalk`     | Binary message passing via UNIX signals              | [Repo](https://github.com/dreule/minitalk) |
| `push_swap`    | Stack-sorting algorithm using custom instructions    | [Repo](https://github.com/dreule/push_swap) |
| `philosophers` | Thread-safe dining philosophers simulation           | [Repo](https://github.com/dreule/philosophers) |

---

## 🧰 Toolbox

- C (strictly norm-compliant)
- POSIX syscalls (`fork`, `execve`, `pipe`, etc.)
- MiniLibX for graphics
- Parsing theory + shell grammar
- Git & Makefiles

---

## 🤝 Let's Connect

- 🌐 [42 Profile](https://profile.intra.42.fr/users/dreule)
- 📫 [LinkedIn](https://www.linkedin.com/in/dreule/) *(optional — let me know if you want it added)*

---

<p align="center">
  <em>"Never memorize what you can visualize." – me, probably</em>
</p>
