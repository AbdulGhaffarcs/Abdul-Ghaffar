/* ============================================================
   Product Popup — Styles
   Snippet: product-popup.liquid
   ============================================================ */

.pp-overlay {
  position: fixed;
  inset: 0;
  background-color: rgba(0, 0, 0, 0.45);
  display: flex;
  align-items: center;
  justify-content: center;
  z-index: 9999;
  padding: 16px;
  opacity: 0;
  visibility: hidden;
  transition: opacity 0.25s ease, visibility 0.25s ease;
}

.pp-overlay.is-open {
  opacity: 1;
  visibility: visible;
}

.pp-modal {
  background-color: #fff;
  box-shadow: 0 2px 4px rgba(0, 0, 0, 0.2);
  width: 100%;
  max-width: 660px;
  max-height: 92vh;
  overflow-y: auto;
  position: relative;
  transform: translateY(20px);
  transition: transform 0.25s ease;
}

.pp-overlay.is-open .pp-modal {
  transform: translateY(0);
}

.pp-close {
  position: absolute;
  top: 10px;
  right: 12px;
  background: none;
  border: none;
  font-size: 1.4rem;
  line-height: 1;
  cursor: pointer;
  color: #333;
  z-index: 10;
  padding: 4px 8px;
  transition: color 0.15s ease;
}

.pp-close:hover {
  color: #000;
}

.pp-body {
  display: grid;
  grid-template-columns: 120px 1fr;
  gap: 20px;
  padding: 36px 20px 24px;
}

.pp-img-wrap {
  flex-shrink: 0;
}

.pp-img {
  width: 120px;
  height: 140px;
  object-fit: cover;
  display: block;
}

.pp-details {
  display: flex;
  flex-direction: column;
  gap: 10px;
}

.pp-title {
  font-family: 'Jost', sans-serif;
  font-weight: 300;
  font-size: 1rem;
  color: #000;
  margin: 0;
  line-height: 1.3;
}

.pp-price {
  font-family: 'Lustria', serif;
  font-size: 1rem;
  color: #000;
  margin: 0;
  line-height: 1.2;
}

.pp-desc {
  font-family: 'Jost', sans-serif;
  font-weight: 300;
  font-size: 0.8rem;
  line-height: 1.5;
  color: #000;
  margin: 0;
}

.pp-variants {
  display: flex;
  flex-direction: column;
  gap: 14px;
  margin-top: 4px;
}

.pp-option-group {
  display: flex;
  flex-direction: column;
  gap: 5px;
}

.pp-option-label {
  font-family: 'Jost', sans-serif;
  font-weight: 400;
  font-size: 0.8rem;
  color: #333;
  letter-spacing: -0.01em;
}

.pp-color-options {
  display: flex;
  border: 0.5px solid #000;
  width: 100%;
}

.pp-color-btn {
  flex: 1;
  padding: 10px 12px;
  background-color: #fff;
  border: none;
  border-right: 0.5px solid #000;
  font-family: 'Jost', sans-serif;
  font-weight: 400;
  font-size: 1rem;
  color: #000;
  text-transform: capitalize;
  cursor: pointer;
  text-align: left;
  letter-spacing: -0.02em;
  transition: background-color 0.15s ease, color 0.15s ease;
}

.pp-color-btn:last-child {
  border-right: none;
}

.pp-color-btn.is-selected {
  background-color: #000;
  color: #fff;
}

.pp-color-btn:hover:not(.is-selected) {
  background-color: #f5f5f5;
}

.pp-size-wrap {
  display: flex;
  border: 0.5px solid #000;
  width: 100%;
  align-items: stretch;
}

.pp-size-select {
  flex: 1;
  appearance: none;
  -webkit-appearance: none;
  background: transparent;
  border: none;
  padding: 10px 12px;
  font-family: 'Jost', sans-serif;
  font-weight: 400;
  font-size: 1rem;
  color: #000;
  cursor: pointer;
  letter-spacing: -0.02em;
  outline: none;
}

.pp-size-chevron {
  display: flex;
  align-items: center;
  justify-content: center;
  width: 36px;
  border-left: 0.5px solid #000;
  pointer-events: none;
  font-size: 0.7rem;
  color: #000;
}

.pp-option-btns {
  display: flex;
  flex-wrap: wrap;
  gap: 6px;
}

.pp-opt-btn {
  padding: 8px 14px;
  border: 0.5px solid #000;
  background-color: #fff;
  font-family: 'Jost', sans-serif;
  font-size: 0.875rem;
  color: #000;
  cursor: pointer;
  transition: background-color 0.15s ease, color 0.15s ease;
}

.pp-opt-btn.is-selected {
  background-color: #000;
  color: #fff;
}

.pp-opt-btn:hover:not(.is-selected) {
  background-color: #f5f5f5;
}

.pp-msg {
  font-family: 'Jost', sans-serif;
  font-size: 0.8rem;
  padding: 8px 12px;
}

.pp-msg--error {
  background-color: #fff0f0;
  color: #cc0000;
  border: 0.5px solid #ffcccc;
}

.pp-msg--success {
  background-color: #f0fff4;
  color: #006622;
  border: 0.5px solid #99ddbb;
}

.pp-atc {
  display: flex;
  align-items: center;
  justify-content: center;
  gap: 20px;
  width: 100%;
  background-color: #000;
  color: #fff;
  border: none;
  padding: 14px 20px;
  font-family: 'Jost', sans-serif;
  font-weight: 400;
  font-size: 0.875rem;
  text-transform: uppercase;
  letter-spacing: 0.1em;
  cursor: pointer;
  margin-top: 6px;
  transition: background-color 0.2s ease, transform 0.15s ease;
}

.pp-atc:hover:not(:disabled) {
  background-color: #222;
}

.pp-atc:active:not(:disabled) {
  transform: scale(0.98);
}

.pp-atc:disabled {
  background-color: #888;
  cursor: not-allowed;
}

.pp-atc-arrow {
  display: inline-block;
  width: 26px;
  height: 1px;
  background-color: #fff;
  position: relative;
  flex-shrink: 0;
}

.pp-atc-arrow::after {
  content: '';
  position: absolute;
  right: 0;
  top: 50%;
  transform: translateY(-50%) rotate(45deg);
  width: 5px;
  height: 5px;
  border-top: 1px solid #fff;
  border-right: 1px solid #fff;
}

@media (max-width: 560px) {
  .pp-body {
    grid-template-columns: 90px 1fr;
    gap: 14px;
    padding: 32px 14px 20px;
  }

  .pp-img {
    width: 90px;
    height: 110px;
  }

  .pp-title {
    font-size: 0.9rem;
  }
}