<h1 align="center">こんにちは、kina です 👋</h1>

<p align="center">
  <img src="https://readme-typing-svg.herokuapp.com?center=true&lines=Passionate+Programmer;Fullstack+Engineer;React+%26+Java+Lover" />
</p>

## 💫 自己紹介

- 🧑‍💻 プログラミングが大好きなエンジニア
- 🌱 現在は **React / Java / Supabase** を学習中
- 🎯 目標は「ゲーム業界のバックエンドを支える存在」になること

## 🛠️ スキルセット

![Java](https://img.shields.io/badge/-Java-007396?style=flat-square&logo=java)
![React](https://img.shields.io/badge/-React-61DAFB?style=flat-square&logo=react)
![Tailwind CSS](https://img.shields.io/badge/-Tailwind-38B2AC?style=flat-square&logo=tailwind-css)
![Supabase](https://img.shields.io/badge/-Supabase-3FCF8E?style=flat-square&logo=supabase)

const awards = [
  {
    date: "2024年8月",
    title: "Blockchain Hackathon",
    award: "🥇 最優秀賞",
    description: "ブロックチェーンを活用した予約譲渡システムを提案・実装"
  },
  {
    date: "2024年11月",
    title: "セキュリティコンテスト",
    award: "🥈 準優勝",
    description: "脆弱性診断ツールの開発による評価"
  },
  {
    date: "2025年3月",
    title: "データ分析コンペ",
    award: "🏅 特別賞",
    description: "SNSネットワークの構造分析・可視化"
  },
];

export default function AwardTimeline() {
  return (
    <div className="max-w-4xl mx-auto my-10 px-4">
      <h2 className="text-3xl font-bold text-purple-800 mb-8 text-center">🏆 受賞歴・コンテスト実績</h2>
      <div className="space-y-8">
        {awards.map((item, i) => (
          <div key={i} className="bg-white shadow-md rounded-xl p-6 border-l-4 border-purple-400">
            <h3 className="text-xl font-semibold text-purple-700">{item.date} - {item.title}</h3>
            <p className="text-lg font-medium text-green-600 mt-1">{item.award}</p>
            <p className="text-gray-700 mt-2">{item.description}</p>
          </div>
        ))}
      </div>
    </div>
  );
}

## 🔗 リンク

- [ポートフォリオサイト](https://kina.dev)
- [Twitter](https://twitter.com/your_twitter)
