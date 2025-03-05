# correct-pseudocode
IF selected_date < current_date THEN
    OUTPUT "Error: Please choose a different date."
ELSE
    CHECK availability for selected_date
    IF no available treehouses THEN
        OUTPUT "Error: No treehouses available on this date."
    ELSE
        OUTPUT "Booking confirmed."
    END IF
END IF
