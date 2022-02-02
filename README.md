  if (Input.GetKeyDown(KeyCode.Space))
        {
            isAnimating = !isAnimating;
            animator.SetBool("isAnimating", isAnimating);
        }
