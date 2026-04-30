---
# Leave the homepage title empty to use the site title
title: ''
summary: ''
date: 2022-10-24
type: landing

sections:
  - block: hero
    content:
      title: "Keiichi Ishizu"
      text: "Electromagnetic Exploration Researcher"
    design:
      background:
        image:
          filename: lake.jpg
          filters:
            brightness: 0.4
        image_size: cover
        image_position: center
      spacing:
        padding: ["12rem", "0", "12rem", "0"]

  - block: resume-biography-3
    content:
      username: admin
      text: '九州大学 工学研究院 助教（2024年12月〜）。電磁誘導を利用した物理探査「電磁探査」の研究者。地熱資源・海底金属資源・火山内部構造の探査に取り組み、特に人工電流源を用いた電磁探査モニタリング手法の開発や、ドローン搭載型の新たな電磁探査システムの開発を進めています。'
      button:
        text: 'CV を見る'
        url: cv/
      headings:
        about: ''
        education: '学歴'
        interests: '研究テーマ'
    design:
      background:
        gradient_mesh:
          enable: false
      name:
        size: md
      avatar:
        size: medium
        shape: circle

  - block: markdown
    content:
      title: '🌊 研究テーマ'
      subtitle: ''
      text: |-
        私は「電磁探査」を専門とする研究者です。掘削なしに地下情報を取得する物理探査技術の中でも、電磁誘導を利用した手法に着目しています。探査対象は主に **地熱資源・海底熱水鉱床・火山内部構造** です。

        近年は人工電流源を使った **電磁探査モニタリング** や、アクセス困難な地域の探査のための **ドローン搭載型電磁探査システム** の開発に取り組んでいます。

        📩 共同研究・お問い合わせはお気軽にどうぞ。
    design:
      columns: '1'

  - block: collection
    id: news
    content:
      title: '最新のトピックス・新着情報'
      text: ''
      filters:
        folders:
          - news
        limit: 5
    design:
      view: compact
      columns: '1'
---
