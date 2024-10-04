import React from 'react';
import { GithubIcon, Headphones, Globe, Mail, Briefcase, GraduationCap, Music } from 'lucide-react';

const GitHubProfile = () => {
  return (
    <div className="max-w-4xl mx-auto p-8 bg-gray-100 rounded-lg shadow-lg">
      <header className="text-center mb-10">
        <h1 className="text-4xl font-bold mb-3">👋 Greetings! I'm followCrom</h1>
        <h2 className="text-2xl font-semibold text-blue-600">⚙️ From Spinning Decks to Spinning Up Servers: A DJ's Journey into Development 🤹</h2>
      </header>

      <section className="mb-10">
        <h3 className="text-2xl font-semibold mb-4">Portfolio: Where Beats Meet Bytes</h3>
        <p className="mb-4">Step into my digital realm where music and code harmonize. My portfolio is a symphony of projects that showcase how I've translated my audio expertise into cutting-edge development skills.</p>
        <a href="https://followcrom.com" target="_blank" rel="noopener noreferrer" className="inline-flex items-center px-6 py-3 bg-blue-500 text-white rounded-full hover:bg-blue-600 transition">
          <GithubIcon className="mr-2" />
          Explore followcrom.com
        </a>
      </section>

      <section className="mb-10">
        <h3 className="text-2xl font-semibold mb-4">Mixing Skills: Where Creativity Meets Technology</h3>
        <ul className="list-disc list-inside space-y-4">
          <li className="flex items-start">
            <span className="text-3xl mr-3">🐍</span>
            <p>As a Python aficionado, I dive deep into data, extracting insights and crafting visualizations that tell compelling stories. My code orchestrates data symphonies, turning raw information into actionable intelligence.</p>
          </li>
          <li className="flex items-start">
            <span className="text-3xl mr-3">📲</span>
            <p>My passion for creation extends to the digital realm, where I architect and build web and mobile applications. Each app is a carefully composed piece, designed to resonate with users and provide seamless experiences across devices.</p>
          </li>
          <li className="flex items-start">
            <span className="text-3xl mr-3">🖱️</span>
            <p>My IT repertoire is a well-tuned ensemble of skills, honed through years of hands-on experience and an insatiable appetite for learning. From system architecture to UX design, I orchestrate technology to create harmonious digital solutions.</p>
          </li>
        </ul>
      </section>

      <section className="mb-10">
        <h3 className="text-2xl font-semibold mb-4">Employment: A Career That Rocks</h3>
        <ul className="space-y-6">
          <li className="flex items-start">
            <Headphones className="mr-3 mt-1 text-blue-500 flex-shrink-0" size={24} />
            <p>For six exhilarating years, I was part of the pulse of British music at BBC Radio One. This experience laid the foundation for my transition into the world of professional DJing, where I learned to read crowds and create unforgettable experiences through sound.</p>
          </li>
          <li className="flex items-start">
            <Music className="mr-3 mt-1 text-blue-500 flex-shrink-0" size={24} />
            <p>As a resident DJ at iconic venues like The Roadhouse and Cafe de Paris, I've had the privilege of setting the soundtrack for countless nights of celebration. My turntables have traveled across Europe, spinning tracks that transcend language barriers and unite people through the universal language of music.</p>
          </li>
          <li className="flex items-start">
            <Briefcase className="mr-3 mt-1 text-blue-500 flex-shrink-0" size={24} />
            <p>I orchestrated a different kind of mix as Co-Director of DJ eXperience. We're on a mission to share the joy of music creation, offering immersive DJ workshops, electrifying parties, and comprehensive music production courses that cater to all ages and skill levels.</p>
          </li>
        </ul>
      </section>

      <section className="mb-10">
        <h3 className="text-2xl font-semibold mb-4">Education: The Rhythm of Learning</h3>
        <ul className="space-y-6">
          <li className="flex items-start">
            <GraduationCap className="mr-3 mt-1 text-blue-500 flex-shrink-0" size={24} />
            <p>My academic journey began with a degree in Multi-Media Communication from the University of Winchester, where I learned to blend various forms of media into cohesive, impactful messages. This interdisciplinary approach has been the backbone of my diverse career.</p>
          </li>
          <li className="flex items-start">
            <GraduationCap className="mr-3 mt-1 text-blue-500 flex-shrink-0" size={24} />
            <p>To keep my skills on the cutting edge, I've completed an intensive Data Science Bootcamp, diving deep into the world of analytics and machine learning. I've also earned certifications from the prestigious University of Michigan, mastered cloud computing with AWS, and become proficient in API development with Postman. This continuous learning equips me with a robust toolkit to tackle complex technological challenges.</p>
          </li>
        </ul>
      </section>

      <section className="mb-10">
        <h3 className="text-2xl font-semibold mb-4">Languages: Communicating Across Borders</h3>
        <div className="flex items-center space-x-4">
          <Globe className="text-blue-500 flex-shrink-0" size={24} />
          <p>My linguistic repertoire includes fluent English and Spanish, allowing me to connect with diverse audiences and collaborate on international projects. I'm also equipped with basic French, expanding my ability to engage with francophone cultures and markets.</p>
        </div>
      </section>

      <section>
        <h3 className="text-2xl font-semibold mb-4">Contact: Let's Collaborate</h3>
        <a href="https://followcrom.com/contact/contact.php" target="_blank" rel="noopener noreferrer" className="inline-flex items-center px-6 py-3 bg-green-500 text-white rounded-full hover:bg-green-600 transition">
          <Mail className="mr-2" />
          Reach Out and Connect
        </a>
        <p className="mt-6">Whether you're looking to collaborate on a groundbreaking project, need a developer who can meet tight deadlines with high standards, or just want to chat about the intersection of music and technology, I'm all ears. My experience in the fast-paced worlds of live radio and nightclub DJing has honed my ability to perform under pressure and deliver exceptional results. Let's create something amazing together!</p>
      </section>

      <footer className="mt-10 text-center">
        <a href="http://followcrom.com" target="_blank" rel="noopener noreferrer" className="inline-block px-6 py-3 bg-blue-100 text-blue-800 rounded-full hover:bg-blue-200 transition text-lg font-semibold">
          Discover More at followCrom.com
        </a>
      </footer>
    </div>
  );
};

export default GitHubProfile;