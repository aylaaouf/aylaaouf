# Ayoub Laaoufi

### Backend & DevOps Engineer

Software Engineering student at 1337 Coding School (42 Network | UM6P), Morocco

I build backend systems and the infrastructure they run on: APIs, databases, containers, and pipelines. I'd rather know *why* something works than just that it does.

```c
#include <stdio.h>

typedef struct s_engineer
{
    const char  *name;
    const char  *role;
    const char  *school;
    const char  *country;
    const char  *obsession;
    const char  *motto;
}   t_engineer;

int main(void)
{
    t_engineer me = {
        .name      = "Ayoub Laaoufi",
        .role      = "Backend & DevOps Engineer",
        .school    = "1337 Coding School (42 Network | UM6P)",
        .country   = "Morocco",
        .obsession = "building backends and the infrastructure they run on",
        .motto     = "reliable software, no magic"
    };

    printf("Hi, I'm %s.\n", me.name);
    return (0);
}
```

---

## $ docker compose up stack

```yaml
services:
  languages:
    image: ayoub/languages
    environment: [C, C++, Python, JavaScript, TypeScript, SQL, Bash]

  backend:
    image: ayoub/backend
    environment: [FastAPI, Django, Node.js, REST, SQLAlchemy]
    depends_on: [databases]

  databases:
    image: ayoub/databases
    environment: [PostgreSQL, MariaDB]

  devops:
    image: ayoub/devops
    environment: [Linux, Docker, Docker Compose, NGINX, CI/CD, Git, Bash]
    depends_on: [backend]

  systems:
    image: ayoub/systems
    environment: [TCP/IP, HTTP/1.1, Sockets, POSIX, Threads, poll()]
    restart: always
```

---

## $ ls -l ~/projects

| Project | What it does | Built with |
|---|---|---|
| [`1337-nexus`](https://github.com/aylaaouf/1337-nexus) | Collaborative platform: project collaboration, team recruitment, AI-powered tools, real-time chat | React, TypeScript, FastAPI, PostgreSQL |
| [`inception`](https://github.com/aylaaouf/inception) | Full WordPress stack on Docker: NGINX, PHP-FPM, MariaDB, Redis, FTP, Portainer, Adminer | Docker Compose |
| [`webserv`](https://github.com/aylaaouf/Webserver) | Non-blocking HTTP/1.1 server with CGI, virtual hosts, uploads, and `poll()` I/O | C++98 |
| [`minishell`](https://github.com/aylaaouf/minishell) | My own Unix shell, a POSIX-style command interpreter | C |
| [`philosophers`](https://github.com/aylaaouf/Philosophers_simulation) | Dining Philosophers: threads, mutexes, deadlock prevention | C, pthreads |
| [`cub3d`](https://github.com/aylaaouf/3D-game) | First-person maze explorer rendered with raycasting | C |

---

## $ cat ~/.roadmap

```bash
while true; do
    build    "CI/CD pipelines and deployment automation"
    learn    "async Python, backend architecture"
    explore  "cloud infrastructure, Linux administration"
    study    "scalable and distributed systems"
    break_it && fix_it
done
```

---

## $ ./contact --all

- **LinkedIn:** [ayoub-laaoufi](https://www.linkedin.com/in/ayoub-laaoufi/)
- **Email:** [ayoub.laaoufi@hotmail.com](mailto:ayoub.laaoufi@hotmail.com)
- **42 Intra:** [aylaaouf](https://profile.intra.42.fr/users/aylaaouf)
