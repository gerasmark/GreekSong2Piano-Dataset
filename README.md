# GreekSong2Piano Dataset

A synchronized dataset of Greek songs and their corresponding piano covers for automatic cover generation research.

## Overview

The GreekSong2Piano dataset contains 659 Greek songs paired with their corresponding piano covers, spanning 8 distinct Greek musical genres. This dataset represents the first synchronized collection specifically designed for Greek music cover generation research.

**Dataset Statistics:**
- **Size**: 659 song-cover pairs
- **Duration**: 41 hours of music
- **Storage**: 42 GB
- **Genres**: 8 Greek musical genres
- **Formats**: Audio (WAV) and symbolic (MIDI)

## Dataset Composition

### Musical Genres

The dataset covers 8 traditional and modern Greek musical genres:

| Genre | Count | Description |
|-------|-------|-------------|
| **Λαϊκό (Laiko)** | 163 | Greek folk songs from 1950s-1960s, evolved from Rembetiko |
| **Μοντέρνο Λαϊκό (Modern Laiko)** | 162 | Contemporary evolution incorporating pop and electronic elements |
| **΄Εντεχνο (Entexno)** | 147 | Sophisticated modern Greek music blending artistry with poetry |
| **Pop** | 74 | Dance-Club music and Greek disco hits |
| **Εναλλακτικό (Enallaktiko)** | 63 | Alternative music fusing Pop Rock and Entexno elements |
| **Rock** | 40 | Greek Rock and 1980s Pop-Rock tracks |
| **Ρεμπέτικο (Rembetiko)** | 19 | Traditional urban folk music with characteristic rhythms |
| **Hip Hop/R&B** | 6 | Greek interpretations of Hip Hop and R&B styles |

### Metadata Format

```yaml
song:
  uploader: "Artist/Channel Name"
  title: "Song Title"
  youtube_id: "YouTube_Video_ID"
  genre: "Genre_Label"
  duration: 240  # seconds

cover:
  uploader: "Arranger Name"
  title: "Cover Title"
  youtube_id: "YouTube_Video_ID" 
  duration: 235  # seconds