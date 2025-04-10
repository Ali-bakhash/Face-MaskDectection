# Mask Classification:

After the face is detected, a deep learning classifier (typically a CNN) predicts if the face has a mask, no mask, or improperly worn mask.

Common architectures: MobileNetV2, ResNet, or VGG fine-tuned on mask datasets.

#  Dataset Examples:

MAFA, RMFD (Real-World Masked Face Dataset), WIDER FACE, or custom datasets created from crowdsourced images.

# Output & Alert System:

Displays a bounding box with labels (e.g., “Mask” or “No Mask”).

Can trigger alerts, deny access, or store logs if no mask is detected.

# Hospital Use Case:

Can be implemented in hospitals to ensure patients, visitors, and staff follow mask protocols, helping reduce infection risk and maintain hygiene standards.
