# Academic Homepage Style Research (30 top-conference authors)

Surveyed 30 well-known LLM / RL / NLP / ML / CV researchers' homepages (29 reachable;
Lianmin Zheng 403'd) to extract the dominant style and imitate it. June 2026.

## Authors surveyed
**RL/LLM:** John Schulman, Sergey Levine, Chelsea Finn, Jason Wei, Tri Dao, Ofir Press,
Tim Dettmers, Shunyu Yao, Lilian Weng, Andrej Karpathy.
**NLP:** Graham Neubig, Danqi Chen, Percy Liang, Tatsunori Hashimoto, Yoon Kim,
Alexander Rush, Sewon Min, Jacob Andreas, Eunsol Choi, Mohit Iyyer.
**ML/CV/systems:** Kaiming He, Lucas Beyer, Albert Gu, Lianmin Zheng, Jure Leskovec,
Aleksander Madry, Jacob Steinhardt, Carlos Guestrin, Song Han, Phillip Isola.

## Dominant style (consensus)
- **Layout:** single-column, centered, narrow ~700–800px. No sidebars. (≈28/30)
- **Color:** white bg, black/dark-gray text, blue links; minimal/no accent. No dark theme
  in the canonical look. Teal links are the only notable minority accent (Tri Dao, Shunyu Yao).
- **Typography:** sans-serif system font stack, near-universal. Serif bodies essentially absent.
- **Header:** photo top-left or top-center + large bold name + one horizontal row of plain
  links — email · Google Scholar · GitHub · CV · X. Two link styles: text/`[ ]`/`·`-delimited
  vs. small icons.
- **Sections / order:** About/Bio → News/Updates → Publications → Teaching/Group → Awards/Service.
  A dated News feed is a recurring signature. Faculty add a Group/Advisees section.
- **Publications:** plain reverse-chronological list — **bold title + authors + venue + inline
  `[paper] [code] [project]` links**. Mostly no thumbnails (thumbnails a minority: Barron, Rush,
  Isola), no abstract boxes. Often grouped by year or kept to "Selected".
- **Template:** overwhelmingly hand-rolled minimal HTML ("Jon Barron minimal" idiom);
  a few use al-folio (Tri Dao), Hugo/PaperMod (Lilian Weng), WordPress, Squarespace, Webflow.

## Imitation decisions applied to this homepage
1. Serif body → **sans-serif system stack**.
2. Navy pill buttons → **plain blue inline links**, `·`-separated, in the header.
3. Removed uppercase micro-headers / abstract boxes → plainer bold section headings + thin rule.
4. Reordered sections so **Publications sits right after News**.
5. Publications reformatted to **bold title + authors (own name emphasized) + venue + inline
   bracket links**, reverse-chronological.
6. Kept a subtle light/dark toggle (al-folio precedent) but light is the clean default.
