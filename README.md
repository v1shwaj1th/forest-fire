# forest-fire
Note on Model Performance: The provided code is fully functional and produces valid predictions, but for optimal results, consider enhancing the model architecture by:

Increasing hidden layers - Add more Conv2D/Dense layers to capture complex patterns

Expanding layer sizes - Try doubling filters (e.g., 32→64→128→256)

Training longer - Increase epochs (50-100) with EarlyStopping patience=10

Adding regularization - Include Dropout(0.3-0.5) and BatchNormalization() between layers

These improvements will boost accuracy while the current implementation serves as a solid baseline. Always monitor validation metrics to prevent overfitting.
