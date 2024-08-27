* Hi there! 👋 it's  `Yasin Alabay` 🌱
```
const mySkills = () => ({
  FULL_STACK: {
    frontend: ["React", "Next.js", "React Native"],
    backend: ["Node.js", "Express.js"],
    database: ["MongoDB", "MySQL"],
  },
  getCurrentFocus() {
    return Object.entries(this.FULL_STACK)
      .map(([area, techs]) => `${area.toUpperCase()}: ${techs.join(", ")}`)
      .join(" | ");
  },
});

console.log(`Current focus: ${mySkills().getCurrentFocus()}`);
```
