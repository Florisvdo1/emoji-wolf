/* General Reset */
* {
  margin: 0;
  padding: 0;
  box-sizing: border-box;
}

/* Prevent scrolling */
html, body {
  overflow: hidden;
  height: 100%;
  width: 100%;
}

/* Body Styling */
body {
  font-family: Arial, sans-serif;
  background: #f8f9fa;
  color: #333;
  display: flex;
  flex-direction: column;
  height: 100vh; /* Use viewport height */
  width: 100vw;  /* Use viewport width */
}

/* Header Styling */
header {
  background: #ffffff;
  border-bottom: 1px solid #ddd;
  padding: 5px 10px;
  flex-shrink: 0;
}

#header-container {
  display: flex;
  justify-content: space-between;
  align-items: center;
}

header h1 {
  font-size: 1.2rem; /* Reduced by 4px if base is 16px */
  text-align: center;
}

.icon-button {
  background: #dc3545;
  color: white;
  border: none;
  padding: 5px 10px;
  cursor: pointer;
  border-radius: 5px;
  font-size: 0.9rem; /* Adjusted for better fit */
}

/* Huiswerk Section */
#huiswerk-container {
  padding: 5px 10px;
  text-align: center;
  flex-shrink: 0;
}

.huiswerk-button {
  width: 100%;
  padding: 10px;
  background: #dc3545;
  color: white;
  border: none;
  border-radius: 5px;
  font-size: 1rem; /* Reduced by 4px if base is 16px */
  cursor: pointer;
  transition: background-color 0.3s ease, color 0.3s ease;
}

.huiswerk-button.green {
  background: #28a745;
  color: white;
}

/* Planner Sections */
#planner {
  flex-grow: 1;
  overflow: hidden;
  display: flex;
  flex-direction: column;
}

.sector {
  flex: 1;
  padding: 10px;
  background: #ffffff;
  border: 1px solid #ddd;
  border-radius: 5px;
  overflow: hidden;
  display: flex;
  flex-direction: column;
  margin: 10px;
}

.sector-header {
  text-align: center;
  flex-shrink: 0;
  margin-bottom: 10px;
}

.sector-header h2 {
  font-size: 1rem; /* Reduced by 4px */
}

.emoji-placeholders {
  display: flex;
  justify-content: space-around;
  align-items: center;
  flex-grow: 1;
}

.emoji-placeholder {
  width: 18%;
  max-width: 60px; /* Increased to prevent overlapping */
  aspect-ratio: 1;
  background: #f0f0f0;
  border: 2px dashed #6c757d;
  border-radius: 5px;
  display: flex;
  align-items: center;
  justify-content: center;
  margin: 2px;
  transition: border-color 0.3s ease, background-color 0.3s ease;
  font-size: 1rem; /* Increased for better visibility */
}

.emoji-placeholder.highlight {
  border-color: #007bff;
  background-color: #dce6f8;
  transform: scale(1.05);
}

.sector-notes {
  margin-top: 10px;
  width: 100%;
  padding: 8px;
  border: 1px solid #ddd;
  border-radius: 5px;
  font-size: 0.9rem;
  flex-shrink: 0;
}

/* Emoji Deck */
#emoji-deck {
  background: #ffffff;
  border-top: 1px solid #ddd;
  padding: 10px;
  flex-shrink: 0;
  display: flex;
  flex-direction: column;
  align-items: center;
}

.emoji-navigation {
  display: flex;
  justify-content: center;
  align-items: center;
  margin-bottom: 5px; /* Added margin to separate from emoji grid */
}

.emoji-navigation button {
  background: none;
  border: none;
  font-size: 1.5rem;
  cursor: pointer;
  margin: 0 10px;
}

.emoji-navigation span {
  font-size: 1rem;
  font-weight: bold;
}

.emoji-grid {
  display: grid;
  grid-template-columns: repeat(auto-fill, minmax(30px, 1fr));
  gap: 5px;
  max-height: calc(2 * (1rem + 10px)); /* Limit to two rows */
  overflow: hidden;
  width: 100%;
  height: calc(2 * (1rem + 10px)); /* Ensures two full rows are visible */
}

.emoji-item {
  font-size: 1.2rem;
  text-align: center;
  cursor: grab;
}

/* Magnet Effect */
.magnet-effect {
  animation: magnet 0.3s forwards;
}

@keyframes magnet {
  0% { transform: scale(1); }
  100% { transform: scale(1.05); }
}

/* Disable user selection */
body, button, input {
  -webkit-user-select: none;
  -ms-user-select: none;
  user-select: none;
}

/* Prevent zooming on input focus */
input {
  font-size: 16px;
}

/* Responsive Design */
@media (max-width: 480px) {
  /* Adjustments for very small screens */
  header h1 {
    font-size: 1rem; /* Reduced by 4px */
  }

  .icon-button {
    font-size: 0.8rem;
    padding: 5px 8px;
  }

  .huiswerk-button {
    font-size: 0.8rem;
    padding: 8px;
  }

  .sector-header h2 {
    font-size: 0.8rem; /* Reduced by 4px */
  }

  .emoji-placeholder {
    max-width: 50px;
    font-size: 0.9rem;
  }

  .emoji-navigation button {
    font-size: 1.2rem;
    margin: 0 5px;
  }

  .emoji-navigation span {
    font-size: 0.9rem;
  }

  .emoji-grid {
    gap: 3px;
    height: calc(2 * (0.9rem + 8px));
    max-height: calc(2 * (0.9rem + 8px));
  }
}

@media (min-width: 600px) {
  /* Adjustments for larger screens */
  header h1 {
    font-size: 1.5rem;
  }

  .icon-button {
    font-size: 1rem;
    padding: 5px 10px;
  }

  .huiswerk-button {
    font-size: 1rem;
    padding: 10px;
  }

  .sector-header h2 {
    font-size: 1rem; /* Reduced by 4px */
  }

  .emoji-placeholder {
    max-width: 60px;
    font-size: 1rem;
  }

  .emoji-navigation button {
    font-size: 1.5rem;
    margin: 0 10px;
  }

  .emoji-navigation span {
    font-size: 1rem;
  }

  .emoji-grid {
    height: calc(2 * (1rem + 10px));
    max-height: calc(2 * (1rem + 10px));
  }
}

@media (min-height: 800px) {
  #emoji-deck {
    height: var(--emoji-deck-height, 150px);
  }

  .emoji-grid {
    height: calc(2 * (1rem + 10px));
    max-height: calc(2 * (1rem + 10px));
  }
}
