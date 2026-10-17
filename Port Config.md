
Control Hub Port Mapping

• Port 0: LM (Left Front Drive Motor)
• Port 1: RM (Left Back Drive Motor)
• Port 2: Shooter (Right Front Drive Motor - 6000 RPM)
• Port 3: Intake (Right Back Drive Motor)

Software Directions and Inversions

• leftFront (LM): DcMotor.Direction.FORWARD
• leftBack (RM): DcMotor.Direction.FORWARD
• rightFront (Shooter): DcMotor.Direction.REVERSE (Swapped)
• rightBack (Intake): DcMotor.Direction.REVERSE (Swapped)

Motor Settings

• Zero Power Behavior: DcMotor.ZeroPowerBehavior.BRAKE
