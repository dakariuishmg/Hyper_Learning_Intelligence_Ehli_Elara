# Hyper_Learning_Intelligence_Ehli_Elara
Hyper-Learning Intelligence: a CEFR-anchored English fluency engine with real-time semantic topology, phoneme mapping, spaced-repetition, HRR embeddings, Markov generation, and adaptive i+1 targeting—zero dependencies, pure vanilla architecture.

# Hyper-Learning Intelligence v41.1

**A CEFR-anchored English fluency engine with real-time semantic topology, phoneme mapping, spaced-repetition, HRR embeddings, Markov generation, and adaptive i+1 targeting—zero dependencies, pure vanilla architecture.**

## Overview

Hyper-Learning Intelligence is a comprehensive language learning platform that combines cutting-edge computational linguistics with evidence-based pedagogy. Built entirely with vanilla JavaScript and localStorage, this system provides an advanced English fluency training environment without requiring any external dependencies or server infrastructure.

### Core Features

- **CEFR Framework Integration**: Content and progression aligned with Common European Framework of Reference levels (A1-C2)
- **Holographic Reduced Representations (HRR)**: Advanced semantic embeddings for meaning-based vocabulary organization
- **Adaptive i+1 Targeting**: Dynamic content difficulty adjustment based on Krashen's Input Hypothesis
- **Spaced Repetition System**: Optimized review scheduling using evidence-based memory algorithms
- **Phoneme Mapping**: Detailed phonetic analysis and pronunciation guidance
- **Semantic Topology**: Real-time visualization of conceptual relationships and vocabulary networks
- **Markov Chain Generation**: Context-aware sentence and dialogue generation for practice scenarios
- **Error Pattern Detection**: Intelligent analysis of learner mistakes with targeted remediation
- **Adaptive Curriculum**: Personalized learning paths based on performance metrics and proficiency gaps

## Architecture

### Technology Stack

- **Frontend**: Pure Vanilla JavaScript (ES6+)
- **Storage**: Browser localStorage API
- **Dependencies**: Zero external libraries
- **Rendering**: Native DOM manipulation

### Key Components

1. **Semantic Engine**: HRR-based word embedding system for semantic similarity calculations
2. **Phonetic Processor**: IPA phoneme mapping and pronunciation analysis
3. **Spaced Repetition Scheduler**: SM-2 and Leitner system hybrid for optimal review timing
4. **Markov Generator**: N-gram based natural language generation for practice content
5. **CEFR Analyzer**: Automatic text complexity assessment and level classification
6. **Progress Tracker**: Comprehensive learning analytics and visualization
7. **Error Classifier**: Machine learning-inspired pattern recognition for common mistakes

## Installation

### Option 1: Direct Download

1. Clone or download this repository:
   ```bash
   git clone https://github.com/yourusername/hyper-learning-v41-1.git
   cd hyper-learning-v41-1
   ```

2. Open `index.html` in a modern web browser:
   ```bash
   # On macOS
   open index.html
   
   # On Linux
   xdg-open index.html
   
   # On Windows
   start index.html
   ```

### Option 2: Local Web Server

For enhanced functionality, serve via a local HTTP server:

```bash
# Using Python 3
python -m http.server 8000

# Using Node.js (requires npx)
npx serve .

# Using PHP
php -S localhost:8000
```

Then navigate to `http://localhost:8000` in your browser.

### Browser Compatibility

- Chrome/Edge 90+
- Firefox 88+
- Safari 14+
- Opera 76+

**Note**: Requires JavaScript enabled and localStorage access.

## Usage

### Getting Started

1. **Initial Assessment**: Complete the CEFR placement test to establish your baseline proficiency level
2. **Profile Setup**: Configure learning goals, preferred study time, and target areas
3. **Daily Practice**: Engage with adaptive exercises tailored to your i+1 level
4. **Review Sessions**: Complete spaced repetition drills based on the system's scheduling algorithm
5. **Progress Monitoring**: Track advancement through the analytics dashboard

### Features Guide

#### Vocabulary Learning

- Browse words organized by CEFR level and semantic clusters
- View HRR-based semantic neighborhoods to discover related terms
- Practice pronunciation using phoneme maps and IPA transcriptions
- Schedule reviews automatically based on your retention performance

#### Sentence Generation

- Generate contextual practice sentences using Markov chains
- Adjust complexity to match your target learning level (i+1)
- Receive instant grammatical and semantic feedback

#### Error Analysis

- Automatic detection of recurring mistake patterns
- Targeted exercises addressing specific error categories
- Progress tracking for common problem areas (articles, prepositions, verb tenses, etc.)

#### Semantic Exploration

- Interactive topology visualization of vocabulary networks
- Explore conceptual relationships through HRR similarity scores
- Discover word families and collocations

### Keyboard Shortcuts

- `Ctrl/Cmd + N`: New exercise
- `Ctrl/Cmd + R`: Review due items
- `Ctrl/Cmd + S`: Save progress
- `Ctrl/Cmd + D`: Toggle dark mode
- `Space`: Next card/question
- `1-5`: Rate difficulty in spaced repetition

## Data Storage

All user data is stored locally in your browser using the localStorage API:

- **Vocabulary Progress**: Learned words, retention scores, review schedule
- **Performance Metrics**: Accuracy rates, response times, error patterns
- **Learning Profile**: CEFR level, preferences, goals
- **Generated Content**: Custom exercises, Markov-generated sentences

**Privacy**: No data is transmitted to external servers. All processing occurs locally.

### Data Export/Import

- Export your progress as JSON for backup purposes
- Import previously saved data to restore learning state
- Transfer data between devices or browsers

## Technical Details

### Holographic Reduced Representations

The system uses HRR (also known as Vector Symbolic Architectures) to create high-dimensional semantic representations:

- **Dimensionality**: 1024-bit binary vectors
- **Operations**: Bundling (superposition), binding (circular convolution), unbinding
- **Applications**: Semantic similarity, word clustering, concept composition

### Spaced Repetition Algorithm

Hybrid approach combining:

- **SM-2 Algorithm**: Interval calculation based on ease factor
- **Leitner System**: Box-based progression with graduated review intervals
- **Adaptive Factors**: Personalized difficulty adjustments based on historical performance

### CEFR Level Mapping

- **A1-A2**: Lexical frequency, basic grammar patterns, common collocations
- **B1-B2**: Intermediate syntax complexity, idiomatic expressions, topic breadth
- **C1-C2**: Advanced discourse markers, nuanced semantics, academic/specialized vocabulary

### Markov Chain Implementation

- **N-gram Order**: Configurable 2-5 gram models
- **Corpus**: CEFR-leveled authentic language samples
- **Constraints**: Grammar-aware generation with syntactic validity checks

## Requirements

### System Requirements

- Modern web browser with ES6+ support
- Minimum 2GB RAM recommended
- 50MB available localStorage space
- Screen resolution: 1024x768 or higher

### Browser Requirements

- **JavaScript**: ES6+ (Arrow functions, Classes, Promises, async/await)
- **Storage**: localStorage API with quota ≥10MB
- **APIs**: Web Audio API (for phonetic playback, optional)
- **CSS**: CSS3 Grid, Flexbox, Custom Properties

### No External Dependencies

This project requires **zero external libraries or frameworks**. All functionality is implemented in vanilla JavaScript, including:

- HRR semantic embeddings
- Spaced repetition algorithms
- Markov chain generation
- Phoneme mapping
- CEFR analysis
- UI components
- Data visualization

## Project Structure

```
hyper-learning-v41-1/
├── index.html              # Main application entry point
├── css/
│   ├── main.css           # Core styles
│   ├── components.css     # UI component styles
│   └── responsive.css     # Mobile/tablet layouts
├── js/
│   ├── core/
│   │   ├── hrr.js        # Holographic Reduced Representations
│   │   ├── spaced-rep.js # Spaced repetition engine
│   │   ├── markov.js     # Markov chain generator
│   │   └── phoneme.js    # Phonetic mapping system
│   ├── modules/
│   │   ├── cefr.js       # CEFR framework implementation
│   │   ├── semantic.js   # Semantic topology analyzer
│   │   ├── errors.js     # Error pattern detection
│   │   └── adaptive.js   # Adaptive i+1 targeting
│   ├── ui/
│   │   ├── dashboard.js  # Main dashboard interface
│   │   ├── exercises.js  # Exercise rendering
│   │   └── visualizer.js # Topology visualization
│   └── app.js            # Application initialization
├── data/
│   ├── vocabulary/        # CEFR-leveled word lists
│   ├── phonemes/          # IPA phoneme mappings
│   └── corpus/            # Training text corpus
└── README.md
```

## Configuration

Customize learning parameters by modifying `js/app.js`:

```javascript
const config = {
  spacedRepetition: {
    initialInterval: 1,      // days
    easyBonus: 1.3,
    minEaseFactor: 1.3,
    maxInterval: 365
  },
  hrr: {
    dimensions: 1024,
    sparsity: 0.1
  },
  markov: {
    ngramOrder: 3,
    maxLength: 20
  },
  adaptive: {
    i1Window: 0.2,           // +20% above current level
    errorThreshold: 0.3      // Trigger review at 30% errors
  }
}
