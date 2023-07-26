function Character(name, age, hobby) {
  this.name = name;
  this.age = age;
  this.hobby = hobby;
}

Character.prototype.bio = function() {
  return `Hi there, I'm ${this.name}, a ${this.age}-year-old who loves working with ${this.hobby}!`;
}

Character.prototype.interests = ['programming', 'studing', 'watching movies'];

const 𝒉𝒂𝒏𝒅𝒚𝒌𝒊𝒍𝒍𝒆𝒓 = new Character('𝒉𝒂𝒏𝒅𝒚𝒌𝒊𝒍𝒍𝒆𝒓', 19, 'coding');
console.log(𝒉𝒂𝒏𝒅𝒚𝒌𝒊𝒍𝒍𝒆𝒓.bio());
console.log(`My interests include: ${𝒉𝒂𝒏𝒅𝒚𝒌𝒊𝒍𝒍𝒆𝒓.interests.join(', ')}.`);
