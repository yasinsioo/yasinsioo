// Hi there! 👋 it's Yasin Alabay 🌱

const mySkills = () => {
  return {
    FULL_STACK: {
      frontend: ["React", "Next.js", "React Native"],
      backend: ["Node.js", "Express.js"],
      database: ["MongoDB", "MySQL"],
    },
  };
};

console.log(
  `Current focus: ${Object.entries(mySkills().FULL_STACK)
    .map(([area, techs]) => `${area.toUpperCase()}: ${techs.join(", ")}`)
    .join(" | ")}`
);
