# CNN+LSTM Model Artifacts (Balanced Data Loading)

## Model Information
- **Model Type**: CNN+LSTM Hybrid
- **Data Loading**: Balanced sampling across activities
- **Total Parameters**: 282,657
- **Input Shape**: (256, 9)
- **Number of Classes**: 33

## Architecture
- **CNN Layers**: 3 Conv1D blocks with filters [64, 128, 128]
- **LSTM Layers**: 2 LSTM layers with units [128, 64]

## Performance Metrics
- **Test Accuracy**: 0.8588
- **Test F1-Macro**: 0.8587
- **Test F1-Weighted**: 0.8587

## Training Information
- **Total Epochs**: 100
- **Best Epoch**: 100
- **Best Validation Loss**: 0.5140
- **Best Validation Accuracy**: 0.8325

## Classes
- 0: Caffeination
- 1: Catch up on what happened
- 2: Check the food provisions
- 3: Clean a spill
- 4: Clean the place
- 5: Clean up
- 6: Cooking
- 7: Dry your clothes
- 8: Eating
- 9: Food and accomodations
- 10: Friends arrives at home
- 11: Get and fold the laundry
- 12: Get home
- 13: Grab cream, sugar and snacks
- 14: Health activity
- 15: Morning exercise
- 16: Perk up with coffee
- 17: Play a board game
- 18: Prepare breakfast
- 19: Read and wait
- 20: Relaxing
- 21: Room Decoration
- 22: Set the table and eat
- 23: Share some vides
- 24: Straighten up
- 25: Talk about the day
- 26: Texting and Reading
- 27: The home tour
- 28: Time to go
- 29: Video game break
- 30: Waking up
- 31: Wash the clothes
- 32: Watch TV

## Data Configuration
- **Window Size**: 256
- **Stride**: 128
- **Subset Size**: 1,000,000 (balanced across activities)

Generated: 2025-11-27 07:01:51
